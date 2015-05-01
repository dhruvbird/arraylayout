# veblayout
Experiments with the Van Emde Boas ordered array layout

This project is about trying different memory layouts for searching in an array. The layouts we try are:

1. sorted: The usual sorted array on which we apply binary search
2. eytzinger: The Eytzinger (or BFS) layout most commonly used implicit binary heaps
3. btree: A (B+1)-ary variant of the Eytzinger layout
3. veb: The van Emde Boas layout from the cache-oblivious literature