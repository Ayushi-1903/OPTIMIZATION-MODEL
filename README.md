# OPTIMIZATION-MODEL
Company Name:CODTECH IT SOLUTIONS

Name: Ayushi Verma

Intern ID :CT6MTNYD

Domain: Data Science 

Durations: 6 months

Mentor:Muzammil Ahmed

# Description of the Task 4 Optimization model:
The notebook focuses on solving a classical Linear Programming (LP) problem using optimization techniques in Python, particularly with the help of the PuLP library. The main objective is to determine the optimal allocation of resources to maximize profit or minimize cost under given constraints.

Problem Overview:
The optimization problem deals with a factory that produces two types of products—Product A and Product B. Each product requires a specific amount of labor and raw material, and each provides a certain profit. The factory has limited resources (labor hours and raw material) and wants to find the best production mix of Product A and B to maximize profit.

Tasks Performed:
Importing Required Libraries:
The notebook starts by importing PuLP, a linear programming package in Python that allows users to define and solve LP problems easily.

Defining the Problem:
The LP problem is formulated with the goal of maximizing the total profit. A LpProblem object is created with LpMaximize as the objective type.

Defining Decision Variables:
Two non-negative decision variables are defined:
x: number of units of Product A
y: number of units of Product B
These represent the quantities to be determined.

Objective Function:
The profit from each unit of Product A and B is given. The objective function is created as:
Profit = 20x + 30y
This function is added to the problem model.

Adding Constraints:
The model is subject to the following constraints:
Labor Constraint: Product A requires 2 hours, Product B requires 3 hours; a maximum of 120 hours is available.
Material Constraint: Product A uses 3 units, Product B uses 4 units; a maximum of 160 units of material is available.

These are formulated and added to the LP model.

Solving the Problem:
The problem is solved using the default solver that comes with PuLP. The solver determines the values of x and y that maximize profit while satisfying the constraints.

Displaying Results:
After solving, the optimal values of x and y and the corresponding maximum profit are printed. The results show how many units of each product should be produced.

Visualization (Optional):
Though not explicitly included in the uploaded notebook, optimization problems like this can be visualized using constraint plots and feasible regions, which aids in better understanding.

![image](https://github.com/user-attachments/assets/f28a493c-ff4c-4ed6-acdb-b04a6ebe420e)
![image](https://github.com/user-attachments/assets/5f8d55bd-3242-4f23-91cd-f1259f9ea67b)

