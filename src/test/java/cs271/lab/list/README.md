## TestPerformance.java questions

#### Question: run test and record running times for SIZE = 10, 100, 1000, 10000, ...
**Size 10:** 836ms

**Size 100:** 848ms

**Size 1000:** 1s

**Size 10000:** 7s

**Size 15000:** 11s

**Size 100000:** 69s

I will be running tests with size 15000.

#### Question: What conclusions can you draw about the performance of LinkedList vs. ArrayList when comparing their running times for AddRemove vs. Access?

**LinkedList:**
* AddRemove: 513ms
* Access: 8s

**ArrayList:**
* AddRemove: 2s
* Access: 512ms

Array-Lists have remarkably faster retrieval compared to Linked Lists, and Linked Lists have substantially faster add and remove time compared to Array-Lists.