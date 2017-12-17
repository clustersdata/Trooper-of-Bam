# Trooper-of-Bam

Trooper of Bam

Description

There is an ancient story about a trooper Salman in the city of Bam, who killed a group of thieves by his intelligent plan. The scenario was as follows: When he arrived to the city he found that each thief guards a street by walking along a part of that street, between two crossroads. Salman also found that all streets of Bam are either vertical or horizontal and the walking speed of all thieves is one kilometer per hour. First for finding thieves he walked randomly along some streets, and in the starting minute of each hour, he wrote down the time and position of the thieves that he could see. We know that the length of each part of a street between two consecutive crossroads was one kilometer, so in the beginning of an hour, each thief was in a crossroad and would be seen by Salman, if Salman had the same x or y coordinate as thief (i.e. Salman and thief are in the same street). Remember that at the beginning of each hour Salman was in a crossroad too. 
Salman knew that at a certain time all thieves would stop their guarding. By having all these information he decided to select the shortest path along which he could see all thieves surely (when they stop their guarding), and shoot them in the smallest period (Salman could shoot a thief whenever he could see him). Note that Salman had seen each thief at leat once. 
Suppose that you know the information that Salman gathered during his random walk and you want to help him finding the smallest path that he will absolutely see all thieves along it.

Input

The input consists of several test cases. In the first line of each test case there are 6 numbers n, p, s, x, y, o which are the number of thieves, the length of the Salman's first pat h (in hour), the stop time in which all thieves will stop, number of vertical and horizontal streets and finally the number of observations that Salman has done during his first path (n < 70, p < 100, s < 35000, x, y < 100) . After this line, there are p lines each consisting of two numbers. The line number l of this p lines shows the coordinates (x, y) of Salman at the starting minute of hour l. After this set of lines, there are o lines each consisting of 4 numbers (t, tm, tx, ty) which means that Salman h as seen thief t on time tm at the point (tx, ty). The test case starting with 6 zeros is the final test case and has no output.

Output

For each test case, print the length of the shortest path in kilometer in a separate line.

Sample Input

1 3 4 3 3 1
1 3
1 2
1 1
1 1 2 3
0 0 0 0 0 0
Sample Output

2
