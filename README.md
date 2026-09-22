# graphs_elijahortiz

This is a Python library for working with graph algorithms.

The library currently includes Dijkstra's shortest path algorithm. It can find the shortest distance and path from a starting vertex to the other vertices in a weighted graph.

## Package files

- sp.py contains the Dijkstra shortest path algorithm
- heapq.py contains the heap implementation used by the algorithm
- test.py loads graph data from a text file and tests the algorithm

## Installation

From the project folder run:

pip install .

## Usage

Example import:

from graphs_elijahortiz import sp

Then the Dijkstra algorithm can be called with:

dist, path = sp.dijkstra(graph, source)

## Testing

Example:

python test.py data\example1.txt

## GitHub Repository

https://github.com/damian-ortiz-elijah/graphs_elijahortiz
