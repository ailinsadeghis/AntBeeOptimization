# AntBeeOptimization

## Overview

This repository contains implementations of two powerful bio-inspired optimization algorithms: **Artificial Bee Colony (ABC)** and **Ant Colony Optimization (ACO)**. These algorithms are designed to solve complex optimization problems, such as the Traveling Salesman Problem (TSP), by simulating the behavior of natural swarms.

## Algorithms

### 1. Ant Colony Optimization (ACO)
The Ant Colony Optimization algorithm is inspired by the foraging behavior of ants. It simulates how ants find the shortest path between food sources and their nest by laying down pheromones that guide other ants.

**Key Features:**
- Pheromone-based path selection
- Heuristic information for guiding ants
- Pheromone evaporation to encourage exploration

### 2. Artificial Bee Colony (ABC)
The Artificial Bee Colony algorithm mimics the foraging behavior of honeybees. It divides the bees into employed, onlooker, and scout bees, each contributing to finding and exploiting food sources (solutions).

**Key Features:**
- Employed bees explore local solutions
- Onlooker bees select solutions based on fitness
- Scout bees explore new areas when solutions stagnate
