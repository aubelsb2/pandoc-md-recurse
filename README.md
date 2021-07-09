# pandoc-md-recurse

This is an example of why recursing would be nice.

Basically the problem I have is that, I would like to be able to specify a "start" document ie, readme.md which directly or indirectly links to every document in relevant hierarchy. Then pandoc to include the documents by appending them and updating links. Also images aren't handled from relative locations.

* Some things to look at [1](1.md)
* Some things to look at [2](imgplus/2.md)
