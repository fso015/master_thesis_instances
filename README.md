# Master Thesis Test Instances
This repository contains the test instances used in the experiments conducted for the master thesis titled "Incorporating Weather Impacts in Vessel Routing and Speed Optimization through Hydrodynamic Modeling: A Heuristic Approach". The test instances are designed to evaluate and validate the proposed solution approach presented in the thesis.

# Test Instance Format
Each test instance file follows a specific format to represent the problem data. The format includes the following information:

- The available vessels. The vessels are named, and all instances include one "Spot"-vessel. 
- The set of orders for the planning horizon. Each order include the type (Delivery/Pickup) and th priority (Mandatory/Optional). It also includes the installation and order size. 
- The length of the planning period and the start-day (given in days from jan. 1st 2010)
- The discretization parameter. (number of discrete timepoints per hour)

Usage
The test instances provided in this repository can be used to replicate the experiments and evaluate the performance of different solution approaches. You can use these instances as inputs for your own algorithms or optimization models.

We hope these test instances will be useful for your research and experimentation. Happy optimizing!