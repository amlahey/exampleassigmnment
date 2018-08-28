# Example Assignment

Write a program to read in a set of locations described by (x,y) coordinates and then a list of people, their location, and a specified radius. For each person, report the number of locations within the radius and the average distance to them.

## Input

Input should be read in using the scanner object as follows:

First, an integer indicating the number of locations. Following this will be that many coordinates given as x followed by y. These coordinates will be double values. After the locations, expect an integer indicating the number of people. Following this will be the information for each person comprised of a single token string name followed by the x and y coordinates of their location as doubles followed by a specified radius. 

## Output

For each person, provide output the reports the persons name, number of locations within the radius, and the average distance to the person of those locations. Match the format of the output in the example below.

## Example

Given the input:

```
5
0.5 1.3
2.7 4.6
-1.2 3.4
-2 -0.5
1.2 2.4
3
Alice 0 0 5
Bob 1.2 2.4 1.2
Carol 10 10 3

```

You should expect the output:

```
Alice is close to 4 locations with average distance: 2.4358061222477447
Bob is close to 1 locations with average distance: 0.0
Carol is close to 0 locations with average distance: 0.0
```

