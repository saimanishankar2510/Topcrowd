# Topcrowd
CHALLENGE DESCRIPTION
OBJECTIVE
Find the minimum time required for Alex to make a certain number of wheels have the same air pressure.

DELIVERABLES
Code snippet in either C, C++ or C# coding language to determine the minimum time required (in minutes).

INSTRUCTIONS
Alex has n wheels with different air pressures. He has a car with m wheel slots. He wants to put m wheels out of n wheels he has, so that he can drive the car. But the car can only have wheels with the same air pressure. He can make the air pressure in a wheel higher or lower by 1, but he can only increase the air pressure maximum of k times, as it is difficult to inflate the wheels. He wants to know how much time he needs to spend to make m number of wheels have the same air pressure. 

function prototype: int getMinimumTime(int input1, int input2, int input3, int[ ] input4)

input1: An integer n - Total number of wheels Alex has.

input2: An integer m - Total wheels Alex would like to put on his car.

input3: An integer k - Maximum number of times Alex can increase the air pressure for a single wheel.

input4: An integer array of size n - Different air pressures on each wheel available with Alex.

output: An integer - Which tells Alex, how many minutes it would take him to make m wheels with same air pressure

 

Example-1

input1: 6

input2: 3

input3: 1

input4: {4, 8, 15, 16, 23, 42}

output: 8

 

Example-2

input1: 5

input2: 4

input3: 0

input4: {5, 5, 5, 4, 5}

output: 0

