# Hash Tables

* Hash Tables /Hash Map a data structure that can map keys to values; the idea of hashing is to distribute the entries (key/value pairs) across an array of buckets/nodes.

1. Hash - A hash is the result of some algorithm taking an incoming string and converting it into a value that could be used for either security or some other purpose. In the case of a hashtable, it is used to determine the index of the array.
2. Buckets - A bucket is what is contained in each index of the array of the hashtable. Each index is a bucket. An index could potentially contain multiple key/value pairs if a collision occurs.
3. Collisions - A collision is what happens when more than one key gets hashed to the same location of the hashtable.

* A collision occurs when more than one key hashes to the same index in an array. As mentioned earlier, a “perfect hash” will never have any collisions.

* The load factor tells us something about how full the hash table is. 



### Hash maps do this to store values:

1. accept a key
2. calculate the hash of the key
3. use modulus to convert the hash into an array index
4. store the key with the value by appending both to the end of a linked list

### Hash maps do this to read value:

1. accept a key
2. calculate the hash of the key
3. use modulus to convert the hash into an array index
4. use the array index to access the short LinkedList representing a bucket
5. search through the bucket looking for a node with a key/value pair that matches the key you were given

## Internal Methods

**Add()** : adding a new key/value pair.

**Find()** : takes in a key, gets the Hash.

**Contains()** : accept a key, and return a boolean on if that key exists inside the hashtable.

**GetHash()** : accept a key as a string, conduct the hash, and then return the index of the array where the key/value should be placed.

References:

* [Intro to Hash Tables](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-30/resources/Hashtables.html)

* [what is a hash table?](https://www.youtube.com/watch?v=MfhjkfocRR0)

* [basics of hash tables](https://www.hackerearth.com/practice/data-structures/hash-tables/basics-of-hash-tables/tutorial/)

* [hash table wiki](https://en.wikipedia.org/wiki/Hash_table)