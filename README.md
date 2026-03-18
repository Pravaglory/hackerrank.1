Task
Given an integer, , perform the following conditional actions:

If  is odd, print Weird
If  is even and in the inclusive range of  to , print Not Weird
If  is even and in the inclusive range of  to , print Weird
If  is even and greater than , print Not Weird
Input Format

A single line containing a positive integer, .

Constraints
1<=n<=100

Output Format

Print Weird if the number is weird. Otherwise, print Not Weird.

Sample Input 0

3
Sample Output 0

Weird
Explanation 0


 is odd and odd numbers are weird, so print Weird.

Sample Input 1

24
Sample Output 1

Not Weird
Explanation 1


 and  is even, so it is not weird.

Language
Python 3
More
1234567891011121314151617181920
#!/bin/python3

import math
import os
import random
import re
import sys




Line: 10 Col: 1

Test against custom input
Congratulations!

You have passed the sample test cases. Click the submit button to run your code against all the test cases.


Sample Test case 0

Sample Test case 1
Input (stdin)
3
Your Output (stdout)
Weird
Expected Output
Weird
BlogScoringEnvironmentFAQAbout
