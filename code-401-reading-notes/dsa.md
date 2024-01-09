# Data Structures and Algorithms

## [Basic Recursion](https://www.youtube.com/watch?v=vPEJSJMg4jY)
- In the video, a hook example described a locked chest with a missing key and the key is stashed somewhere in a box within a main box. What is the algorithm (process) for searching for the missing key?
- Recursion is used in many algorithms
- Pseuedo code is used as a method for explaining, not to demonstrate actual code logic

## [Data Structures you MUST know](https://www.youtube.com/watch?v=sVxBVvlnJsM)
- 5 different data structures:
    - Linked list: 
        - Linear stucture where elements are stored in nodes. Each node contains a value and a pointer (connects to the next node in the chain)
        - First node is the head and last is the tail
        - Adv: adding new items and deleting items
        - Dis: retrieving items and searching items
    - Array:
        - Stores a fixed-size sequence of elements of the same type.
        - Adv: retrieving items
        - Dis: adding items may not be as efficient
    - Hash table:
        - Maps keys to value
        - Adv: add + remove and retrieving items
        - Dis: key collisions
    - Stack + Queue
        - Stack: Last in, first out 
        - Queue: First in, first out
        - Adv: efficient add + remove
        - Dis: limited use cases
    - Graphs + Trees
        - Collection of nodes and edges that connect pairs of nodes

## [Big O Explained](https://www.youtube.com/watch?v=v4cd1O4zkGw)

- Big O describes how time scales with respect to the input variable

- Summarizing the pigeon and internet transfer story:
    - Regardless of the data size, the pigeon needs to fly a specific distance
    - However, the amount of data vs time to transfer data is a linear function
    - Pigeon O(1) for constant time
    - Internet transfer O(N) where N = amount of data

- Big O rules:
    1. Different steps get added:
        - O(a) (step 1)
        - O(b) (step 2)
        - = O(a+b)
    2. Drop constants
        - O(2N) is actually O(N) 
    3. Different inputs => Different variables
        - It is not O(N^2) but instead O(a*b)
    4. Drop non-dominate terms
        - O(n+n^2) => O(n^2)
        - n^2 what really drives and dominates the rate of change 

## Additional Resources

[8 Common Data Structures](https://towardsdatascience.com/8-common-data-structures-every-programmer-must-know-171acf6a1a42)

[Why Big O](https://web.archive.org/web/20230207075759/https://triplebyte.com/blog/why-you-should-learn-big-o-and-stop-hacking-your-way-through-algorithms)

## Discussion Questions
1. What is 1 of the more important things you should consider when deciding which data structure is best suited to solve a particular problem?
- The efficiency of the data stucture and the memory required to run the algorithm
2. How can we ensure that we’ll avoid an infinite recursive call stack?
- A recursive function has two parts - a base case (when the function doesn't call itself) and a recursive case (when the function calls itself again)
- This is typically seen by including an if else statement 
- Example from video:
<pre>
<code>
def countdown(i):
    print(i)
    # base case
    if i <= 1:
        return
    # recursive case
    else:
        countdown(i-1)
</code>
</pre>
- If the countdown is equal or less than 1, then the base case is met and the function will stop. If the countdown is greater than 1, then the else statement will run

### Things I want to know more about
- What is the actual definition of a recursive function and how does it differ from a loop?