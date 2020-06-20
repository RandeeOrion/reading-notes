# HashTables 

**Is a HashTable useful for search or sorting operations? Why?**

- Yes, because in theory, if you can hash a 'key' then you can quickly and easily pull the info out of a bucket rather than traversing the entire array. 

**What makes a good hash function?**

- A great hash function will never have any 'collisions' or have two 'objects' in the same bucket


**Why should you try to reduce the number of collisions?**

- so that there is less traversing to do. If there is only one object in a bucket, then once you get to that bucket you can simply access the data inside rather than sort through that bucket. 


**What is stored at each index of a HashTable? Why?**

- Each index of the hashtable stores the info that is confected to the 'key' that has been hashed and is assigned to that bucket.
