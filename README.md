# Algorithms-DataStructures

Hold my beer😊
# Linear Search Algorithm
In a linear search, we search an element in a given array by traversing the array from the starting till the desired element or value is found.

-Time Complexity: O(n)

# Implementing Linear Search
Following are the steps of implementation that we will be following:

1. Traverse the array using a for loop.
2. In every iteration, compare the target value with the current value of the array.
    - If the values match, return the current index of the array.
    - If the values do not match, move on to the next array element.
3. If no match is found, return -1.

To search the number 5 in the array given below, linear search will go step by step in a sequential order starting from the first element in the given array

<img src="https://www.studytonight.com/data-structures/images/linear-search-array.png" width="400" height="150" align="center">

## How it works <br/>

*Input: values[] = {5, 34, 65, 12, 77, 35} <br/>
target = 77  <br/>
Output: 4    <br/><br/>
Input: values[] = {101, 392, 1, 54, 32, 22, 90, 93} <br/>
target = 200 <br/>
Output: -1 (not found)*
