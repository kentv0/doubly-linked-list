Doubly Linked List
======
Description
------
The project details can be viewed in the document [here](https://github.com/kentv0/doubly-linked-list/blob/master/prompt.pdf).

Get Started
------
### 1. Clone repository
```
    $ git clone https://github.com/kentv0/doubly-linked-list.git
```
### 2. Compile package
```
    $ cd doubly-linked-list
    $ javac data_structures/*
```
### 3. Run test driver 1
```
    $ java data_structures.Driver1
```
```
    Expected output:
    2% completed
    4% completed
    6% completed
    8% completed
    10% completed
    12% completed
    14% completed
    16% completed
    18% completed
    20% completed
    22% completed
    24% completed
    26% completed
    28% completed
    30% completed
    32% completed
    34% completed
    36% completed
    38% completed
    40% completed
    42% completed
    44% completed
    46% completed
    48% completed
    50% completed
    52% completed
    54% completed
    56% completed
    58% completed
    60% completed
    62% completed
    64% completed
    66% completed
    68% completed
    70% completed
    72% completed
    74% completed
    76% completed
    78% completed
    80% completed
    82% completed
    84% completed
    86% completed
    88% completed
    90% completed
    92% completed
    94% completed
    96% completed
    98% completed
    10  9  8  7  6  5  4  3  2  1
    1  2  3  4  5  6  7  8  9  10
```
### 4. Run test driver 2
```
    $ java data_structures.Driver2
```
```
    Expected output:
    -- Now Testing addFirst: Expect 10-1 . . .
    10 9 8 7 6 5 4 3 2 1

    Note: Iterated through 10 items
    Complete
    Elapsed Time: 4.783518 mS

    -- Now Testing addLast: Expect 1-10 . . .
    1 2 3 4 5 6 7 8 9 10

    Note: Iterated through 10 items
    Complete
    Elapsed Time: 0.090954 mS

    -- Now Testing find( new Integer ) . . . Complete
    Elapsed Time: 3140.935575 mS

    -- Now Testing contains( new Integer ) . . . Complete
    Elapsed Time: 3148.323802 mS

    -- Now Testing removeFirst: expect 0 item iteration . . . . . . . . . . . . .


    Note: Iterated through 0 items
    Complete
    Elapsed Time: 0.164535 mS

    -- Now Testing removeLast: expect 0 item iteration . . . . . . . . . . . . .


    Note: Iterated through 0 items
    Complete
    Elapsed Time: 0.155849 mS

    -- Now Testing remove( new Object ): removing first set of odd numbers . . .
    24 22 20 18 16 14 12 10 8 6 4 2 1 2 3 4 5 6 7 8 9 10 11 12 13 14 15 16 17 18 19 20 21 22 23 24 25

    Note: Iterated through 37 items
    -- Now Testing remove( new Object ): removing second set of odd numbers . . .
    24 22 20 18 16 14 12 10 8 6 4 2 2 4 6 8 10 12 14 16 18 20 22 24

    Note: Iterated through 24 items
    -- Now Testing remove( new Object ): removing first set of even numbers . . .
    2 4 6 8 10 12 14 16 18 20 22 24

    Note: Iterated through 12 items
    -- Now Testing remove( new Object ): removing second set of even numbers . . .


    Note: Iterated through 0 items
    Complete
    Elapsed Time: 0.523497 mS

    -- Now Testing ConcurrentModificationException with reported size: 10 . . . Complete
    Elapsed Time: 0.068471 mS

    -- Now Testing Stack Implementation . . . Elapsed Time: 9.112011 mS

    -- Now Testing Queue Implementation . . . Elapsed Time: 6.817465 mS

    Testing complete. Farewell.
```
### 5. Clean
```
    $ rm -rf data_structures/*.class
```
### 6. Debug
* Ignore the following output during compile
    ```
    Note: Some input files use unchecked or unsafe operations.
    Note: Recompile with -Xlint:unchecked for details.
    ```
