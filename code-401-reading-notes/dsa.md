# Data Structures and Algorithms

## [Basic Recursion](https://www.youtube.com/watch?v=vPEJSJMg4jY)
- In the video, a hook example described a locked chest with a missing key and the key is stashed somewhere in a box within a main box. What is the algorithm (process) for searching for the missing key?
- Recursion is used in many algorithms
- Pseuedo code is used as a method for explaining, not to demonstrate actual code logic

## Discussion Questions
- What is 1 of the more important things you should consider when deciding which data structure is best suited to solve a particular problem?
- How can we ensure that we’ll avoid an infinite recursive call stack?
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