# Micro—ACT-R (tentative)
> **”ACT-R at a Micro-Scale”**

<img width="2160" height="793" alt="image" src="https://github.com/user-attachments/assets/5a64ecfa-eade-4c7f-a436-0151328d0a4a" />

## What makes this different from standard ACT-R?
**Standard ACT-R operates on a macro level with production rules. This project zooms into the micro-level of cognitive processing.**

## Overview
**Micro–ACT-R operates through a clear, fully explainable pipeline from input to reasoning and execution:**

> First, text is acquired from the **Environment** and parsed in the **Input** stage into individual cognitive **particles** (Particle Encapsulation).

> Next, during **Reasoning**, the system uses **Topological Mapping** to define relationships between particles and assigns explicit spatial coordinates via **Spatial Allocation**. These coordinates are logged directly into **Storage**.

> The system then validates consistency between the category of knowledge and past experiences **(Match & Select)**, selects the appropriate action based on this consistency **(Execution)**, and finally produces the **Output**.

# Pipeline Architecture
<img width="1042" height="921" alt="image" src="https://github.com/user-attachments/assets/576380f0-34bc-46d3-ae6a-e359d0d663ed" />

```text
Input→Reasoning→Output

Reasoning:
[Particle Encapsulation]→[Topological Mapping]→[Spatial Allocation]→[Memory/Storage]→[Match&Select]→[Execution]
```

**"The Reasoning module is the core engine, structured into six internal sub-processes (Particle Encapsulation,Topological Mapping,Spatial Allocation,Memory/Storage, Match&Select, and Execution) to perform fine-grained context inference."**

# Core Repositories:
## Input:
> **The core processing logic for Environment and Input.**
- [input-parser](https://github.com/ao-labs-123/input-parser)

## Reasoning: 
> **Implementation of Reasoning stages.**
- [particle encapsulation](https://github.com/ao-labs-123/particle-encapsulation)
- [topological-mapper](https://github.com/ao-labs-123/topological-mapper)
- [spatial allocation]()
- [memory-storage]()
- [match-and-select]()
- [execution-engine]()

## Output: 
> **Practical application for Output/Decision-making.**
- [output-formatter]()

# Join the Research
**If you believe in the future of logical rule-based architectures, a star would mean a lot to support this independent research. 🌟**
