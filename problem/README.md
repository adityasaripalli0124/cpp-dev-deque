# Implementing a "deque" - Doubly Ended Queue

**Deque** is similar to a dynamic array with the ability to resize itself automatically when an element is inserted or deleted, with their storage being handled automatically by the container.

- They support insertion and deletion from both the ends in an amortized constant time - O(1).
- Inserting and erasing in the middle is linear in time - O(n).

## What is expected as a solution ?

The C++ standard specifies that a legal (i.e., standard conforming) implementation of deque must satisfy the following requirements:

|Feature         |Description                    |
|----------------|-------------------------------|
|deque()         |`initialize a blank deque.`    |
|deque(n, x)     |`initialize a deque of length n with all values as x.`    |
|push_back(x)    |`append data x at the end.`    |
|pop_back()      |`erase data at the end.`       |
|push_front(x)     |`append data x at the beginning.`       |
|pop_front()      |`erase data at the beginning.`       |
|front()      |`Returns the first element(value) in the deque.`       |
|back()      |`Returns the last element(value) in the deque.`       |
|empty()      |`Returns true if deque is empty else returns false.`       |
|size()      |`Returns the current size of deque.`       |
|resize(s,d,direction)    |`Changes the size dynamically. 's' is the new size of the deque and 'direction' is either 1(forward) or -1(reverse). If the new size is greater than the current size of the deque, then increase the size at the end (if direction is set to 1) or increase the size at the beginning of the deque (if the direction value is set to -1) and then fill the empty space with the default value d. If the new size of the deque is less than the current size then remove elements at the end (if direction = 1) or remove elements at the begining (if direction = -1).`       |
|clear()      |`Remove all elements of deque.`       |
|D[n]      |`Returns the nth element of the deque. If n<0 then traverse the deque in reverse. Eg: D[-1] = last element.`       |
|print()   |`Print all the elements in the deque.`|


You can rename the current file by clicking the file name in the navigation bar or by clicking the **Rename** button in the file explorer.

## Evaluation Parameters
Accuracy of operations and performance.

## Important Guidelines for the implementation

- Use only C++ as programming language.
- DO NOT use any of the C++ STL libraries like vectors/maps/queue etc. You need to implement your own data structures and handle the memory management yourself.
- The deque implemented should be generic which should support any data type, like int/float/string or any user defined data types like objects instantiated from any structure or class (Hint: use templates).
- Follow PHYP Coding guidelines for naming conventions and others coding details.
- Write appropriate test cases to test your code. Try all the data types int/float/double/string. Also create some structure - for example: create a Student class/structure with member variables like {name, roll-no, section, gender, etc} and then try to create multiple student objects and perform all the operations of deque on it.
- PLAGIARISM is strictly prohibited and online solutions from websites like stack-exchange etc, will not be tolerated. I can figure out if the solution is copied from somewhere. So, avoid such short-cuts and work on the problem on your own.
- Avoid using online C++ compilers. Install "command-line-tools" in your macbook (which will install g++ compiler) and use it.
- Ask for help if needed.

## Deadline

**11th Oct, 2023 (Wednesday)**

