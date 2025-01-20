# Top-K-Frequent-Elements
Given an integer array nums and an integer k, return the k most frequent elements. You may return the answer in any order.
Explanation:
Frequency Map:
Count the frequency of each element using a HashMap.
Min-Heap:
Use a min-heap (priority queue) to store the most frequent 
𝑘
k elements.
If the heap size exceeds 
𝑘
k, remove the least frequent element.
Result Extraction:
Extract all elements from the heap into an array.
Complexity:
Time Complexity: 
𝑂(𝑛log⁡𝑘)
O(nlogk), where 𝑛 is the length of the input array.
𝑂(𝑛)O(n) for building the frequency map and
𝑂(𝑛log⁡𝑘)O(nlogk) for heap operations.
Space Complexity: 
𝑂(𝑛)O(n) for the frequency map and the heap.






