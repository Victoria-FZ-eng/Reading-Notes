# GraphQL @connection

@connection is used to specify relationships between @model types

* one-to-one connection

```
type Project @model {
  id: ID!
  name: String
  team: Team @connection
}

type Team @model {
  id: ID!
  name: String!
}
```

* one-to-many connections

```
type Post @model {
  id: ID!
  title: String!
  comments: [Comment] @connection(keyName: "byPost", fields: ["id"])
}

type Comment @model
  @key(name: "byPost", fields: ["postID", "content"]) {
  id: ID!
  postID: ID!
  content: String!
}
```

* Many-to-many connections

```
type Post @model {
  id: ID!
  title: String!
  editors: [PostEditor] @connection(keyName: "byPost", fields: ["id"])
}

# Create a join model and disable queries as you don't need them
# and can query through Post.editors and User.posts
type PostEditor
  @model(queries: null)
  @key(name: "byPost", fields: ["postID", "editorID"])
  @key(name: "byEditor", fields: ["editorID", "postID"]) {
  id: ID!
  postID: ID!
  editorID: ID!
  post: Post! @connection(fields: ["postID"])
  editor: User! @connection(fields: ["editorID"])
}

type User @model {
  id: ID!
  username: String!
  posts: [PostEditor] @connection(keyName: "byEditor", fields: ["id"])
}
```

for more information , check the references below.

References : 

* [review: Intro to Serverless](https://hackernoon.com/what-is-serverless-architecture-what-are-its-pros-and-cons-cc4b804022e9)

* [review: AWS Amplify Kool-Aid](https://aws.amazon.com/amplify/)

* [GraphQL @connection section](https://docs.amplify.aws/cli/graphql-transformer/connection/)