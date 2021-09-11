# Contigo

The Amplify Auth category provides an interface for authenticating a user. Behind the scenes, it provides the necessary authorization to the other Amplify categories. It comes with default, built-in support for Amazon Cognito User Pool and Identity Pool. The Amplify CLI helps you to create and configure the auth category with an authentication provider.

here is how to start using auth in amplify: 

1. `amplify add auth`
2. `amplify push`
3. add dependency -> `  implementation 'com.amplifyframework:aws-auth-cognito:1.24.0'` to app build.gradle
4. 
```
Amplify.addPlugin(new AWSCognitoAuthPlugin());
Amplify.configure(getApplicationContext());
```

for more information check the reference below

References:

1. [Amplify and Cognito](https://docs.amplify.aws/lib/auth/getting-started/)