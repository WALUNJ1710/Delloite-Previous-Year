# Delloite-Previous-Year
## Problem 1: Class Monitor

*Problem Statement* :

After JEE Mains, some students got admission into an engineering college. Now there is a class consisting of such n students, and the HOD came to say it is time to select the class monitor. But He never gets all of them at one time. So he brought a register, every time he gets someone with less rank than the previous time he cut the name and wrote the name of the student and the rank.
For a given number of ranks he gets each time, you have to predict how many names are cut in the list.

*Constraints*:
Number of Visiting<=10^9
ranks <=10000

*Input Format*:
Number of Visiting N in their first line
N space separated ranks the HOD gets each time

*Output Format*:
Number of ranks cut in the list

*Sample Input*:
6
4 3 7 2 6 1

*Sample Output*:
3

## Problem 2 : Corona for Computer  
*Problem Statement* :

Every decimal number can be changed into its binary form. Suppose your computer has it’s own CoronaVirus, that eats binary digits from the right side of a number. Suppose a virus has 6 spikes, it will eat up 6 LSB binary digits in your numbers.
You will have a bunch of numbers, and your machine will have a virus with n spikes, you have to calculate what will be the final situation of the final numbers.

*Input Format:*
First line, a single Integer N
Second line N space separated integers of the bunch of values as array V
Third line a single integer n, the number of spikes in Corona for Computer

*Output Format:*
Single N space separated integers denoting the final situation with the array v.

*Sample Input:*
5
1 2 3 4 5
2

*Output:*
0 0 0 1 1

*Explanation:*
5 is 101 in binary, when you cut the last two binary digits, its 1.
