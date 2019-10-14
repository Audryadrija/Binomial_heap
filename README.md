# Binomial_heap

Binomial Heap is an extension of Binary Heap that provides faster union or merge operation together with other operations provided by Binary Heap. .......
Min-oriented priority queue implemented with the Binomial Heap data
structure implemented with the BinomialHeap class. It supports:

    - Insert element in a heap with n elemnts: Guaranteed logn, amoratized 1
    - Merge (meld) heaps of size m and n: O(logn + logm)
    - Delete Min: O(logn) 
    - Peek (return min without deleting it): O(1)
The heap should have the following structure:

                    17
                   /  \
                  #    31
                      /  \
                    20    34
                   /  \  /  \
                  #    # #   #
