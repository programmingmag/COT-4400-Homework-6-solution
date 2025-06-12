# COT-4400-Homework-6-solution

Download Here: [COT 4400 Homework 6 solution](https://jarviscodinghub.com/assignment/cot-4400-homework-6-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

1. Analyze the worst-case time complexity of the algorithm below. Please
show all work. The b c symbols represent the floor (“round down”) function. You may assume that this function takes Θ(1) time for any input.
You may also assume it takes a constant amount of time to determine
whether an integer is odd.
Note that figuring out what problem this algorithm solves is irrelevant to
analyzing its complexity.
Input: n: nonnegative integer
1 Algorithm: LoopMystery
2 sum = 0
3 t = 1
4 d = 1
5 k = n
6 while k > 1 do
7 for i = 1 to k do
8 t = t + d
9 sum = sum + t
10 end
11 if k is odd then
12 d = −d
13 end
14 k = bk/2c
15 end
16 return sum

