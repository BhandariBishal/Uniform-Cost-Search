# Uniform-Cost-Search
A Python implementation of Uniform Cost Search algorithm for finding the shortest path in a weighted graph.

**Features**
Finds shortest path between start and goal nodes
Uses priority queue for efficient path finding
Supports weighted directed graphs
Returns complete path traversal

**Usage**

graph = {
    'A': [('B', 4), ('C', 1)],
    'B': [('A', 4), ('D', 3)],
    'C': [('A', 1), ('F', 5)]
}

result = uniform_cost_search('A', 'F', graph)
print(" -> ".join(result))

**Input Format**
Graph is represented as a dictionary
Keys are node names
Values are lists of tuples (neighbor_node, cost)
Costs must be positive numbers

**Requirements**
Python 3.x
heapq module (standard library)
