---
icon: box-taped
---

# Containers

Containers are used to store and manage collections of objects. They provide various ways to organize and access data, and they come with built-in functionalities for manipulation; It contains 4 types of containers:

<figure><img src="../../.gitbook/assets/image (7).png" alt=""><figcaption></figcaption></figure>

1.  **Sequence Container**:&#x20;

    Such as `vector`, `list`, `deque`; which stores element in sequential order.
2.  **Associative Container**:

    Such as `set`, `map`, `multiset`, `multimap`, `hash_set`, `hash_map`,  `hash_multiset`, `hash_multimap`; which stores element in such way that allows fast retrieval based on key.
3.  **Unordered Associative Container**:

    Such as `unordered_set`, `unoedered_map`; which provide average constant time complexity.
4.  **Container Adaptors**:

    Such as `stack` , `queue`, and `priority_queue`;  which provide specific interface to oher container.

<table data-full-width="false"><thead><tr><th>Container Type</th><th>Container Name</th><th>Description</th><th>Key Features</th></tr></thead><tbody><tr><td><strong>Sequence Containers</strong></td><td><code>vector</code></td><td><p>A dynamic array that can grow in size.</p><p> </p><p>Provides fast random access and is efficient for adding/removing elements at the end.</p></td><td><ul><li>Dynamic size</li><li>Fast access</li><li>Contiguous memory allocation</li></ul></td></tr><tr><td></td><td><code>deque</code></td><td>A double-ended queue that allows fast insertion and deletion at both the front and back.</td><td><ul><li>Fast insertions/deletions at both ends</li><li>Non-contiguous memory allocation</li></ul></td></tr><tr><td></td><td><code>list</code></td><td>A doubly linked list that allows fast insertions and deletions from anywhere in the list.</td><td><ul><li>Bidirectional traversal</li><li>Efficient insertions/deletions</li></ul></td></tr><tr><td><strong>Associative Containers</strong></td><td><code>set</code></td><td>A collection of unique elements, sorted by their value.</td><td><ul><li>Unique elements</li><li>Automatically sorted</li><li>Fast search, insert, and delete</li></ul></td></tr><tr><td></td><td><code>map</code></td><td>A collection of key-value pairs, where keys are unique and sorted.</td><td><ul><li>Unique keys</li><li>Sorted by keys</li><li>Fast search, insert, and delete</li></ul></td></tr><tr><td></td><td><code>multiset</code></td><td>Similar to <code>set</code>, but allows duplicate elements.</td><td><ul><li>Allows duplicates</li><li>Automatically sorted</li></ul></td></tr><tr><td></td><td><code>multimap</code></td><td>Similar to <code>map</code>, but allows duplicate keys.</td><td><ul><li>Allows duplicate keys</li><li>Sorted by keys</li></ul></td></tr><tr><td><strong>Unordered Associative Containers</strong></td><td><code>unordered_set</code></td><td>A collection of unique elements, not sorted, allowing for average constant-time complexity for lookups.</td><td><ul><li>Unique elements</li><li>Fast average time complexity for search/insert/delete</li></ul></td></tr><tr><td></td><td><code>unordered_map</code></td><td>A collection of key-value pairs, where keys are unique and not sorted.</td><td><ul><li>Unique keys</li><li>Fast average time complexity for search/insert/delete</li></ul></td></tr><tr><td></td><td><code>unordered_multiset</code></td><td>Similar to <code>unordered_set</code>, but allows duplicate elements.</td><td><ul><li>Allows duplicates</li><li>Fast average time complexity for search/insert/delete</li></ul></td></tr><tr><td></td><td><code>unordered_multimap</code></td><td>Similar to <code>unordered_map</code>, but allows duplicate keys.</td><td><ul><li>Allows duplicate keys</li><li>Fast average time complexity for search/insert/delete</li></ul></td></tr><tr><td><strong>Container Adapters</strong></td><td><code>stack</code></td><td>A LIFO (Last In, First Out) data structure that allows adding and removing elements from one end only.</td><td><ul><li>LIFO order</li><li>Limited interface (push, pop, top)</li></ul></td></tr><tr><td></td><td><code>queue</code></td><td>A FIFO (First In, First Out) data structure that allows adding elements at the back and removing from the front.</td><td><ul><li>FIFO order</li><li>Limited interface (push, pop, front, back)</li></ul></td></tr><tr><td></td><td><code>priority_queue</code></td><td>A data structure that allows access to the highest (or lowest) priority element first.</td><td><ul><li>Elements are ordered by priority</li><li>Limited interface (push, pop, top)</li></ul></td></tr></tbody></table>
