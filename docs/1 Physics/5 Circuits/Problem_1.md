# Problem 1: Equivalent Resistance Using Graph Theory

---

## ⚡ Motivation

Computing equivalent resistance in electrical circuits is foundational in physics and engineering. Traditional methods based on identifying series and parallel combinations work well for simple circuits, but quickly become inefficient or unclear in complex topologies.

**Graph theory** provides a more flexible and powerful tool:  
- Nodes = circuit junctions  
- Edges = resistors with weights (resistance values)  
- Reduction = combining edges via algorithmic rules

This method allows us to approach circuits as data structures, simplifying them using logic and algorithms — especially useful in simulation, optimization, and automation.

---

## 🧠 Concept Overview

In a graph-based representation of a circuit:
- **Series connection** = two edges sharing a node with only two total connections → can be combined linearly
- **Parallel connection** = multiple edges connecting the same two nodes → combine via reciprocal sum

Using graph traversal and reduction techniques, we can reduce an entire network to a single equivalent resistor between two nodes.

---

## 🔄 Task Options

### Option 1: Algorithm Description

Write a pseudocode algorithm that:

- Detects series and parallel resistor patterns
- Iteratively reduces the graph
- Handles nested configurations and updates the structure until a single edge remains

### Option 2: Full Implementation (Recommended)

Implement a Python script (e.g. with `networkx`) that:

- Accepts a circuit graph as input
- Supports arbitrary combinations and cycles
- Computes and returns the equivalent resistance
- Includes test cases for:
  - Simple series/parallel circuits
  - Nested resistor networks
  - Multi-loop configurations

---

## 📦 Deliverables

- Pseudocode or full implementation of the algorithm
- Description of algorithm steps (with examples)
- Output for 3 test circuits of increasing complexity
- Optional: performance notes and ideas for optimization

---

## 🔧 Simulation & Code 

### 🔌 Visualized Example Circuit

The following diagram shows the example circuit graph, with resistors labeled on each edge. Nodes represent junctions in the network, and edges represent resistors:

![Circuit Diagram](https://i.imgur.com/HVZJdAT.png)
