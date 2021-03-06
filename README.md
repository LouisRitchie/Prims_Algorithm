# Minimum Spanning Tree Finder
## Implements Prims Algorithm in Java

## Java application with user interface that demonstrates the action of Prim's Algorithm for Minimum Spanning Trees.

![Using the MST finder](MST.gif)

## Running this code on Linux / OSX
- Have java installed
- In `/src/graphtheorydriver`, run `javac *` to compile bytecode
- In `/src` directory, `java graphtheorydriver.Prim_MainFrame` to open the application window

## Running on Windows
- You'll be running similar commands to those I listed above, but I've never run this on Windws.

## About this project
- Simple OO programming project totalling 500 LOC
- I was 20 when I made this
- The work took 20 hours total
- Wanted to get a software co-op but I had nothing to show for programming experience
- Referenced the appendices of a Java textbook that detailed a graphics library's API
- Didn't get the job.

## About Minimum Spanning Trees
Trees are an incredibly important area of study in the field of Graph Theory. These mathematical objects are cycle free, connected
graphs that are used to enhance search efficiency, route planning, or network pathing. Prim's algorithm was developed in the 20th
century and finds a Minimum Spanning Tree in any connected, simple, weighted graph. A Minimum Spanning Tree is characterized by
having the least expensive path from the start vertex to the ending vertex. Other such algorithms are Kruskal's algorithm and
Dijsktra's algorithm.

Prim's algorithm works using the "connected" property of trees - The algorithm connects the start vertex to the rest of the
vertices until the tree spans the graph. Kruskal's algorithm works using the "cycle-free" property of trees, adding the cheapest
edges to the tree as long as they do not form a cycle. Dijsktra's algorithm assigns each vertex in the graph a "cheapest route"
number that is infinty for all vertices outside the "fringe" (vertices one edge away from the current tree) and is a real number
for vertices in the fringe.
