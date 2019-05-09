---
layout: essay
type: essay
title: What I Have Been Learning In Computer Science
# All dates must be YYYY-MM-DD format!
date: 2019-04-27
labels:
  - CS
  - Design Patterns
  - CS Education
  - Algorithms
---

  <img class="ui medium left floated image" src="../images/factory-pattern.gif"/>

## How I have been learning computer science in college

  Recently, I have learned about a term called 'design patterns'. What design patterns are are essentially accepted known ways to solve a problem or accomplish something. This method could be an exact method to accomplish said task, or it could be a way to construct a solution. This term was originally created by engineers to ensure quality products by having standard practices to follow, however it has been adapted to fit within the realm of software engineering as well. For example, the design pattern 'singelton' is a design pattern in which you want to make a sort of global variable, however, you don't have a proper method to do so. Instead, you can create a singleton class, that has a maximum of one instance, and you can modify and access this singleton using functions. I am currently in my fourth semester of college as a Computer Science major, and I realized that I have been taught many of the the things I learned design patterns to solve problems.
  
## Learning and using what smart people took long and hard to figure out
  
  Since the beginning of college, I have been taught how to do things and how to solve problems using the things that I have learned. I have never really been forced to create my own entirely original solution to a problem, but rather I have been learning accepted ways to solve such problems. Currently, I am in a class called Algorithms. In this class I have been learning a lot (it is a tough class), but I have learned many ways to create efficient solutions. At some point, these algorithms had to have been invented by someone. For example, there is an algorithm called Dijkstra's Algorithm. This algorithm is a method that finds the shortest path distance from a source vertex s to every vertex in a weighted graph G. The specifics of the algorithm isn't important to go into detail on, but if you can read the pseudocode it is pretty interesting on how it does it: 
  
```
Dijkstra(G, w, s)
  Initialize-Single-Source(G, s)
  S = {}
  Q = G.V
  while Q != {}
    u = Extract-Min(Q)
    S = S U {u}
    for each vertex v of G.Adj[u]
      Relax(u, v, w)
```
  
  This algorithm is a commonly accepted method to solve such a problem because it is efficient (O(E lg V)), however it does not work on graphs that have edges of negative weights. In any case, this is an example of one of the many things I have learned in college so far. It is a method to solve a problem that has been invented by someone and accepted to be a good solution for it. This is much like engineering, although I am not as experienced in engineering, a design pattern could be something like the best way to build a roof for a house.
  
