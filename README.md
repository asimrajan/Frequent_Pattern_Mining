# Frequent Pattern Mining HandsOn

* Exploring the properties of dataset.
* Understanding the problem with pattern mining
* Implementing the following algorithms:
    - <b>Apriori</b> (Level-Wise / Breadth First approach)
            - Apriori is optimal in terms of No. of queries/candidates that we count.
            - Computation Complexity:  <b> O(2<sup>l</sup> . |D| . l) </b> where |D| is size of data and l is length of longest itemset
    - <b>ECLAT </b>(Vertical / TID set based approach)
            - Can be done using either BFS or DFS or any other hybrid search
            - In ECLAT, all support computation is done using the TIDSet intersections (and hence "practically" much fast).  
            - Computational Complexity: O(2<sup>l</sup>. |D|)
    - <b>FPGrowth </b> 
            - Projection + Prefix Tree Indexing
            - Computational Complexity : O(2<sup>l</sup>. |D|)
* Itemset Summarization - Generating the following Itemsets:
    - Frequent 
    - Maximal
    - Closed
    
* Comparing results and execution time of the above mentioned algorithms and itemset generation.

* Discovering frequent SubSequences and SubStrings
