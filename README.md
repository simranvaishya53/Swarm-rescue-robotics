# Swarm-rescue-robotics
## Introduction to Cohort Intelligence
Cohort Intelligence (CI) is a system of artificial intelligence where a group of candidates, referred to as a cohort, interact and compete with one another to achieve a shared goal. Each candidate is programmed to improve its own behavior by learning from every other candidate within the cohort. This approach is powerful because it harnesses collective experience and adapts to new conditions, drawing inspiration from the collaborative aspects of natural organisms. A cohort's behavior is considered saturated when, after numerous learning attempts, the behavior of all candidates does not significantly improve and becomes indistinguishable.

## FOLLOW ITSELF - A Variation of CI
One of the many variations of Cohort Intelligence is the 'Follow Itself' rule. In this paradigm:
Each candidate c, where c=1,…,C, follows its own predefined behavior.
The behavior of other candidates does not influence the path followed by any candidate.
This rule promotes diversity in the search space and is effective in finding the optimal solution for both uni-modal and multimodal functions.
![image](https://github.com/simranvaishya53/Swarm-rescue-robotics/assets/53307243/78707819-aabb-4dbe-bc8a-1e697a7524c5)

## Problem Statement
This project applies the principles of swarm robotics within a 2D environment to aid in disaster management, utilizing Cohort Intelligence to navigate and complete tasks.

## About the Project
Our 2D simulated environment is populated with autonomous bots, each equipped with vision capabilities, operating among various obstacles and points of interest. The project has two main objectives:

### Objective-1
Maximize the area covered by the candidates and detect points of interest within the environment using a variation of Cohort Intelligence.

### Methodology for Objective 1: 
![image](https://github.com/simranvaishya53/Swarm-rescue-robotics/assets/53307243/c67a5a00-6308-4562-88b3-2263f4227054)

### Objective-2
Utilize a variation of Cohort Intelligence to guide the candidates toward an exit from the environment.

### Methodology for Objective 2: 
![image](https://github.com/simranvaishya53/Swarm-rescue-robotics/assets/53307243/9b56976a-6ed0-4d78-ae53-506d3af56720)

## The project evaluates the following cases:
1) No Obstacle Case: The environment is free of obstacles, allowing candidates to move freely.
2) Static Obstacle Case: The environment contains non-moving obstacles that the candidates must navigate around.

## Future scope 
In an expanded three-dimensional scope, a practical application of this project could be in the field of fire hazard management. Here, the autonomous bots would be tasked with a critical mission: navigating through environments afflicted by fire to identify potential sources of ignition, such as malfunctioning circuit boards. These points of interest are often the culprits behind electrical fires and represent a significant risk factor for the spread of flames.
The advanced algorithms guiding these bots would allow them to intelligently and safely maneuver around the fire-affected zones, ensuring they avoid the immediate dangers posed by the fire itself. By pinpointing these malfunctioning circuit boards, the bots not only assist in the current crisis by identifying the fire's origin but also contribute valuable data for preventing future incidents. The bots become invaluable assets in both the mitigation of ongoing disasters and the enhancement of preventive safety measures.
