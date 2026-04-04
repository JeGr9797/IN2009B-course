# IN2009B Optimization Course Material

This repository contains Jupyter notebooks and supporting material for the **IN2009B course at Tecnológico de Monterrey**. The content focuses on **mathematical optimization models** and their **computational implementation in Python**, covering fundamental topics in location, production planning, routing, and scheduling.

The material is designed for **teaching and learning purposes**, combining mathematical formulations, modeling insights, and computational examples that help students understand how optimization models are formulated and how they can be **approached in practice** (yes I know that not all the cases MIP formulations are the best, this is for learning purposes).

---

## Course contents

The repository is organized into three main modules:

### 1. Location
This module introduces classical location models used in operations research and supply chain design.

Topics include:
- P-median
- P-center
- P-dispersion
- Uncapacitated Facility Location Problem (UFLP)
- Capacitated Facility Location Problem (CFLP)
- Stronger formulations for CFLP

### 2. Production and Capacity
This module covers selected optimization models related to production planning and capacity decisions.

Topics include:
- Dynamic lot-sizing
- Flexibility design problem

### 3. Routing and Scheduling
This module presents representative routing and scheduling problems, together with different modeling approaches and computational tools.

Topics include:
- Traveling Salesman Problem (TSP)
- Efficient TSP formulations (Branch-and-Cut)
- Vehicle Routing Problem (VRP)
- Capacitated Vehicle Routing Problem (CVRP)
- CVRP with PyVRP
- Job Shop Scheduling

---

## Repository structure

The organization of the repository is as follows:

```text
IN2009B-optimization-course/
├── README.md
├── intro/
│   ├── 00_course_welcome.pptx
│   └── 01_mathematical_programming_review_gurobipy.ipynb
├── notebooks/
│   ├── 01_location/
│   ├── 02_production_and_capacity/
│   └── 03_routing_and_scheduling/


```
## Module overview

| Module                  | Main topics                                                                      | Format                  |
| ----------------------- | -------------------------------------------------------------------------------- | ----------------------- |
| Introduction            | Course presentation and mathematical programming review in Python                | Presentation + notebook |
| Location                | P-median, P-center, P-dispersion, UFLP, CFLP, stronger CFLP formulations         | Jupyter notebooks       |
| Production and Capacity | Dynamic lot-sizing, flexibility design                                           | Jupyter notebooks       |
| Routing and Scheduling  | TSP, efficient TSP formulations, VRP, CVRP, CVRP with PyVRP, job shop scheduling | Jupyter notebooks       |

## How to use this repository

This repository is intended to be used as course support material. Students are encouraged to:

* Review the notebooks in the suggested order.
* Read the explanations and mathematical formulations included in each notebook.
* Execute the code cells step by step.
* Modify parameters and data to better understand the behavior of the models.
* Use the notebooks as a basis for experimentation and discussion in class.

## Google Colab environment

The notebooks in this repository are primarily designed to be run in Google Colab. This makes the material easier to use in class and reduces the need for local setup.

Using Google Colab allows students to:

* Run notebooks directly from the browser.
* Avoid many local installation issues.
* Execute Python code in a preconfigured environment.
* Share notebook-based material easily.

Although the notebooks are intended for Colab, they can also be executed in a local Jupyter environment if the required packages are installed.

## Software considerations

Some notebooks require external optimization or routing libraries.

Gurobi

Several notebooks rely on Gurobi for solving mathematical programming models. Running these notebooks requires:

The gurobipy package.
Access to a valid Gurobi license if the size of the problem increases.


PyVRP

The notebook on CVRP with PyVRP uses the pyvrp package as an alternative framework for vehicle routing problems.

GILP

The introductory notebook uses gilp to visualize how simplex algorithm works.

## Intended audience

This material is mainly intended for:

* Students enrolled in the IN2009B course at Tecnológico de Monterrey.
* Students (bachelor degree) interested in optimization modeling with Python.

## Author

José Emmanuel Gómez Rocha

Tecnológico de Monterrey
