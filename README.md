# Eli-Index
String Prefix search Index for the ranked keywords optimized for mobile and has zero lag initialization time.
Most of the prefix search indices are designed for server side use,they store index in the RAM so that has intialization latency which prenvents opening application more faster in mobile.
Eli-Index is designed over AVL Tree,Segmented Tree and Heap.Its nodes has the feature of both AVL Tree and Segmented Tree.It makes prefix search over AVL Tree ,and gets the result list in sorted order while iterating on the nodes of segmented tree.It might also be the first AVL Tree implemented for string prefix search as I couldn't find any paper or implementation that use AVL Tree for string Prefix Search.Eli-Index has preferred to use AVL Tree instead of Trie Index because if Trie Index is implemented in Hard Drive,Either it is fast and uses more memory or it is slower.
