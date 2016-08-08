# Distributed-HashTable

•	Simple Key-Value storage based on Chord design.

•	Simplified version of Chord, covers three things:

    o	ID space partitioning/re-partitioning.
    o	Ring based routing
    o	Node joins


•	SHA-1 hash function is used to lexically arrange nodes in a ring and find the location for a particular key to be stored.

•	Each node maintains a successor and predecessor pointer for nodes in the ring.

•	Content Provider is NoSQL storage that:
    o	The first column should be named as “key”. This column is used to store all keys.
    o	The first column should be named as “value”. This column is used to store all values.

•	However, Node failures, concurrent node-joins and finger tables are not implemented.

