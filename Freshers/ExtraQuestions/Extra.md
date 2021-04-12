### This are the questions I encountered, which are not exactly DSA/related to DSA but require some additional thinking
1. Suppose you have a stack, how will you reduce the time complexity of finding the max of elements currently in stack (near to O(1))
    - What about second max (again O(1))
    - What if we remove some elements, then how will you find max/second max/third max from the stack (again O(1))?

2. Suppose different phone numbers have different call rate, based on the digits of the number. You have n no. of people calling continuously and you want them to know the price before calling to minimise the same.
    - How will you find the cost of the call (per min/per sec) instantaneously?
    - The number of such number - price mapping could be in billions
    - Trust me, hashing, regular expression, nothing worked
