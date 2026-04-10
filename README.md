<a id="readme-top"></a>

<h1 align="center">Emergency Resource Allocation System</h1>

<p align="center">
  Intelligent system for optimizing emergency resource allocation using algorithmic decision-making.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-4C78A8"/>
  <img src="https://img.shields.io/badge/Algorithm-Optimization-F58518"/>
  <img src="https://img.shields.io/badge/Approach-Greedy%20%7C%20Dynamic%20Programming-54A24B"/>
  <img src="https://img.shields.io/badge/Status-Completed-E45756"/>
</p>
<br>

## Table of Contents

1. [Overview](#overview)  
2. [Key Features](#key-features)  
3. [Getting Started](#getting-started)  
4. [Usage](#usage)  
5. [Technical Details](#technical-details)  
6. [License](#license)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
<br>

<br>

## Overview

This project simulates a disaster response system that allocates limited emergency resources efficiently during earthquake scenarios.

<br>

### System Architecture

<p align="center">
  <img src="static/screenshots/system-diagram.png" width="700"/>
</p>

<p align="center">
  High-level workflow of the emergency resource allocation system
</p>

<br>

It demonstrates how algorithmic decision-making can improve response effectiveness under constraints.

Core components include:
- Multi-factor priority scoring
- Optimization algorithms
- Performance evaluation

<p align="right">(<a href="#readme-top">back to top</a>)</p>
<br>

<br>

## Key Features

- Multi-factor priority scoring system  
- Greedy optimization for fast allocation  
- Dynamic programming for optimal comparison  
- Performance benchmarking  
- Visualization of allocation and runtime  
- Trade-off analysis between speed and optimality  

<p align="right">(<a href="#readme-top">back to top</a>)</p>
<br>

<br>

## Getting Started

### Requirements

- Python 3.10+
- pip
- Jupyter Notebook

<br>

### Installation

```bash
pip install numpy pandas matplotlib
```

<br>

### Run

```bash
jupyter notebook
```

<br>

### Open:

```text
Emergency_Resource_Allocation_Algorithm_(Earthquake).ipynb
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>
<br>

<br>

## Usage

- Define disaster regions  
- Compute priority scores  
- Allocate resources  
- Compare algorithms  
- Analyze results  

<p align="right">(<a href="#readme-top">back to top</a>)</p>
<br>

<br>

## Technical Details

### Priority Model

The system calculates a priority score based on:

- Severity (urgency)  
- Damage (impact level)  
- Accessibility (transportation ease)  

Formula:

```text
Score = 2 × Severity + 1.5 × Damage + Transportation
```

<br>

### Algorithms

**Greedy Approach**
- Sort regions by priority score  
- Allocate resources sequentially  
- Time complexity: O(n log n)  
- Advantage: fast  

**Dynamic Programming**
- Evaluates optimal allocation combinations  
- Higher computational cost  
- Advantage: optimal solution  
<br>

### Evaluation

The system compares:

- Allocation efficiency  
- Resource distribution quality  
- Runtime performance  

Key Result:

> Greedy achieves significantly faster runtime, while Dynamic Programming provides optimal allocation results.

<br>

### Runtime Performance Comparison

<p align="center">
  <img src="static/screenshots/runtime.png" width="800"/>
</p>

<p align="center">
  Comparison of execution time between Greedy and Dynamic Programming algorithms.
</p>
<br>

### Resource Allocation Visualization

<p align="center">
  <img src="static/screenshots/allocation.png" width="800"/>
</p>

<p align="center">
  Distribution of allocated resources across disaster regions.
</p>

<p align="right">(<a href="#readme-top">back to top</a>)</p>
<br>

## License

This project is licensed under the MIT License.  
See the [LICENSE](LICENSE) file for details.

<p align="right">(<a href="#readme-top">back to top</a>)</p>
