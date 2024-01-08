# Class 01

## [Pain and Suffering](https://codefellows.github.io/code-401-python-guide/curriculum/class-01/notes/pain_suffering)
- This upcoming course is going to be painful but it's a positive type of pain that results in meaningful growth
- Suffering is different from pain because suffering does not result in meaningful growth
- Don't suffer in silence. Reframe it as pain and an opportunity to grow

### Questions
1. In the context of the reading “Pain and Suffering,” describe the main challenges faced by beginners when learning Python and suggest at least two strategies for overcoming these obstacles.
- Syntax differences from other coding languages and use of identation to frame code blocks.
- Use online resources to include ChatGPT to help explain pain points in syntax differences and indentation.
- Use in-class resources like other students and TAs to help explain or reinforce understanding of topics

## [Beginners Guide to Big O](https://robbell.io/2009/06/a-beginners-guide-to-big-o-notation)
- Big O notation describes the performance or complexity of an algorithm
- Can be used to describe the execution time required by an algorithm and can describe the worst-case scenario in terms of efficiency
- Logarithms are associated with algorithms that have a time complexity of O(log n)
    - Summarized example of its process:
    - Takes the median of a data set and compares to the target value.
    - If it matches, then it returns complete
    - If it does not match, then it will half the data set again and compare to the target value
    - Repeat until successful

### Questions
After reading “Beginners Guide to Big O,” explain the concept of time complexity and space complexity.
- Time complexity describes the amount of time it takes for an algorithm to complete 
- Space compleixty describes the amount of memory required for an algorithm to exeucute

## [Names and Values in Python](https://www.youtube.com/watch?v=_AEJHKGk9ns)
- Names are assigned independently
    - ex.
<pre>
<code>
x = 23
y = x
x = 12
# x was reassigned to 12 but y is still assigned to 23
</code>
</pre>
- Assignments never copy data.
    - ex. 
<pre>
<code>
nums = [1, 2, 3]
other = nums
# other references the same list as nums. it does not copy the nums list
</code>
</pre>
- Immutable types (elements cannot be modified once created): ints, floats, strings, tuples
- Changing an int: is rebinding
<pre>
<code>
x = x + 1 
# this will make a new int
</code>
</pre>
- Changing a list: is mutating
<pre>
<code>
nums.append(7)
# this does not make a new object
</code>
</pre>
### Questions
Based on the “Names and Values in Python” reading, explain the difference between mutable and immutable data types in Python.
- Mutable data types can be modified and any changes to the object affect the original object
    - ex. lists
- Immutable data types cannot be modified and any changes to the object creates a new object
    - ex. ints, floats, strings, tuples

## Additional Resources

## [Season 1, Episode 6, A friendly intro to Big O Notation](https://www.codenewbie.org/basecs/8)

## [Python Module of the Week](https://pymotw.com/3/index.html)

## Things I want to know more about

- What is an example or use case that helps describe the purpose of Big O notation?
    - Example from ChatGPT: a scenario with a list of items and you want to find if a specific number is in the list
    - Iterate through the list until the specific number is found
    - Time complexity: O(n), where n is the size of the list
    - Worst case: need to check entire list