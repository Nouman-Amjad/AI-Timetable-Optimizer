# AI Timetable Optimizer

## Overview
The **AI Timetable Optimizer** is an automated system designed to create optimized university timetables. By leveraging a genetic algorithm-based approach, the project addresses scheduling complexities such as minimizing conflicts between sections, professors, and rooms while ensuring efficient resource allocation.

---

## Features

### 1. Problem Formulation
- **Objective**: Optimize the timetable's fitness function by minimizing conflicts and efficiently allocating resources.
- **Constraints**:
  - Classroom availability.
  - Professor workload.
  - Course distribution across semesters.
  - Scheduling preferences.

### 2. Genetic Algorithm Implementation
The project employs a genetic algorithm to solve the scheduling problem, featuring:

#### a. Initialization
- Defined constants such as course names, lab names, and room names.
- Calculated `DecodeIndex` values for efficient chromosome encoding and decoding.

#### b. Chromosome Generation
- Chromosomes represent timetables, encoding details like course, section, professor, day, time, and room.
- Constraints enforced during chromosome creation include:
  - Room size.
  - Professor workload.
  - Balanced course distribution.

#### c. Fitness Evaluation
- A fitness function evaluates the quality of each chromosome by:
  - Penalizing conflicts between sections, professors, and rooms.
  - Incorporating hard and soft constraints.

#### d. Selection, Crossover, and Mutation
- **Selection**: Used roulette wheel selection to choose parent chromosomes based on fitness values.
- **Crossover**: Combined genetic material from two parents to create new chromosomes.
- **Mutation**: Introduced random changes to promote genetic diversity.

#### e. Population Evolution
- Evolved the population over multiple generations.
- Fitter chromosomes were selected for reproduction.
- Genetic operators explored the solution space, improving timetable quality.

---

## Results

### Final Outcome
- Successfully generated optimized timetables for university courses and labs.
- Minimized conflicts between sections, professors, and rooms.
- Ensured efficient utilization of resources.

### Performance of Genetic Algorithm
- Demonstrated effectiveness in tackling complex timetabling problems.
- Provided a scalable and adaptable solution for university scheduling needs.

---

## Conclusion
The **Timetable Scheduling Project** achieved its objectives by creating an automated system for generating university timetables. By leveraging genetic algorithms, the project:
- Produced optimized schedules that met the university\u2019s constraints and requirements.
- Showcased the potential of genetic algorithms in solving complex scheduling problems.

### Future Enhancements
1. Fine-tune genetic operators to improve algorithm performance.
2. Incorporate additional constraints to reflect real-world complexities.
3. Integrate real-time data for dynamic scheduling.

---

## How to Use the System

### 1. Input Data
- Define courses, sections, professors, and rooms.
- Specify hard and soft constraints as per scheduling requirements.

### 2. Run the Algorithm
- Initialize the population with random chromosomes.
- Evolve the population using selection, crossover, and mutation.
- Evaluate the fitness of each chromosome and select the best solutions.

### 3. Output Timetable
- View the generated timetable with minimized conflicts.
- Export the timetable for implementation.

---

## Acknowledgments
This project was developed as part of the **AI-2002 Artificial Intelligence** course by **Muhammad Nouman Amjad**. Special thanks to the faculty for their guidance and support.

---

## License
This project is licensed under the [MIT License](LICENSE).
