# Graph Operations

A C++ project implementing Dijkstra's algorithm using custom data structures (graph, min-heap, and stack). Uses g++ compilation.

## File Structure

- **data_structures.h**: Data type definitions.
- **graph.h / graph.cpp**: Graph creation, edge insertion, and Dijkstra's algorithm.
- **heap.h / heap.cpp**: Min-heap implementation.
- **stack.h / stack.cpp**: Stack operations for path reconstruction.
- **util.h / util.cpp**: Command-line parsing and file I/O utilities.
- **main.h / main.cpp**: Main program and instruction processing.

## Compilation

To compile the project, run:
make

## Usage

./PJ3 &lt;INPUT_FILE&gt; &lt;GRAPH_TYPE&gt; &lt;FLAG&gt;

    <InputFile> = Path to the graph data file
    <GraphType> = "DirectedGraph" or "UndirectedGraph"
    <Flag>      = "0" or "1"

## Input File Format

First line: 
    &lt;numVertices&gt; &lt;numEdges&gt;

Each subsequent line:
    &lt;EdgeIndex&gt; &lt;VertexU&gt; &lt;VertexV&gt; &lt;Weight&gt;

## Available Commands:
- Stop: Terminates the program.
- PrintADJ: Prints the adjacency list of the graph.
- SinglePair: Computes and prints the shortest path from a source vertex to a destination vertex.
- SingleSource: Computes and prints shortest paths from a single source to all reachable vertices.
- PrintLength: Prints the length of the shortest path between two vertices.
- PrintPath: Prints the actual shortest path between two vertices.
