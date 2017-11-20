# Nice-Milk

Nice Milk

Description

Little Tomy likes to cover his bread with some milk. He does this by putting it in the cup so that one of its sides (called bottom side) touches the bottom of the cup, just as the picture below: 


Since the milk in the cup is limited, only part of the bread is covered with milk(as shown in the pictures). That is, only the area between the surface of the milk and the bottom side of the bread is covered. Note that the distance between these two lines is always h - the depth of the milk, which is also known to him. 
Tomy wants to cover this bread with largest possible area of milk in this way, but he doesn't want to do more than k actions. Help him, will you? 
(You may assume that the cup is wide enough, wider than any side of the bread, so it's possible to cover any side completely) 

Input

The input will contain no more than 10 test cases. Each test case begins with a line containing three integers n,k and h (3<=n<=20, 0<=k<=8, 0<=h<=10). A piece of bread is guaranteed to be a convex polygon of n vertices. In the following n lines, each line contains two integers xi and yi(0<=xi,yi<=1000), representing the Cartesianism coordinate of the ith vertex. The vertices are anti-clockwise numbered. The test case containing n=0, k=0, h=0 will terminate the input, you should not give an answer to this case.

Output

Output the area of the largest possible area of bread covered with milk with two decimal places. Output one line for each test case.
Sample Input

4 2 1
1 0
3 0
5 2
0 4
0 0 0

Sample Output

7.46
