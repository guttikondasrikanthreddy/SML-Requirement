**Project Title**: SML Requirements

**Short Description**:
This project demonstrates Java implementations of essential numerical operations, including calculating averages, identifying the largest number, and running custom simulations. It uses modular, object-oriented design principles, allowing each program to operate independently. The project provides a foundational structure for handling small-scale data manipulation tasks, adaptable to various use cases.

**Overview**:
With a focus on simple yet versatile numerical operations, the SML Requirements project features three Java programs designed to tackle specific computational tasks. These tasks include calculating averages, finding the largest number in a set, and running customizable simulations. By leveraging Java's object-oriented capabilities, each module offers flexibility and reusability, ideal for integration into larger applications or standalone execution.

**Research Question**:
How can fundamental data processing tasks, such as calculating averages and finding the largest number, be implemented in a modular and efficient way using Java?

**Project Goals**:
1. Implement modular Java programs for common numerical operations.
2. Demonstrate the application of object-oriented principles in small-scale data tasks.
3. Provide a basis for further development or integration into larger projects requiring numerical calculations.
   
**Data Source**: kaggle
Input Type: User-provided data arrays or simulated data inputs.
Attributes: Numeric arrays for calculation, including integers and doubles, processed according to specified tasks.
Output Variables: Results include calculated averages, the largest number identified, and any custom simulation outputs.

**Technologies Used**:
Java: Core language for program structure, encapsulation, and computation.
JUnit : Used for testing program methods to ensure functionality and reliability.

**System Architecture**:
Data Input: User inputs numerical data arrays or sets, either from command-line inputs or within the code.
Core Computation: Each program class independently performs specific computations based on input data.
Output Results: Results of computations, such as averages or the largest number, are printed or returned.
Simulation: Simulation class provides customizable simulations based on defined input parameters.

**Classes Overview**:
1. AverageCalculator.java
Purpose: Calculates the average of a given set of numbers.
Methods: Accepts an array of numbers and returns the average.
Usage: Useful for basic statistical computations within data sets.

2. LargestNumberFinder.java
Purpose: Identifies the largest number from an input array.
Methods: Iterates through the array to determine and return the highest value.
Usage: Applicable in sorting algorithms, decision-making processes, and data analysis.

3. Simulator.java
Purpose: Runs a customizable simulation based on input parameters.
Methods: Includes various simulation methods, potentially including random number generation and event-based processes.
Usage: Suitable for scenarios requiring iterative processing or scenario analysis.

**Results**:
Average Calculation: Accurately computes the average of input data sets, validating functionality for common statistical tasks.
Largest Number Identification: Efficiently finds the maximum value, demonstrating the effectiveness of linear searches in Java.
Simulation Output: Produces defined outputs based on input parameters, illustrating custom logic execution within simulations.

**Conclusion**:
The SML Requirements project demonstrates the effectiveness of Java in handling core data processing tasks through modular, object-oriented programs. Each class is designed to be reusable and adaptable, facilitating integration into more extensive applications or fulfilling standalone requirements for numerical operations.
