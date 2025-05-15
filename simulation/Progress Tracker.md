# Progress Tracker

### 17. März:
---
- [x] Mesa documentation introduction
- [x] Mesa simulation angefangen
- [x] Erste Drone und Simulation angefangen
- [x] move()
- [x] tell_position()

### 18. März:
---
- [x] Mesa documentation visualization
- [x] Drone visualisiert im Grid
- [x] coverage() method
- [x] Visited locations

### 19. März:
---
- [x] A* implemented
- [x] Multiple goals possible wrt battery and closest distance

### 24. März:
---
- [x] Path visualization eingebaut - funktioniert bis jetzt aber nur für eine Drone (Agent)
- [x] Call mit Travis
- [x] Learnings: Focus on validating my reasons to implement something!! --> Focus on the research question, the rest can be added always: --> step-by-step

### 25. März:
---
- [x] Implemented the goal class agent more or less (sometimes it gives an error which I could not fix yet)

### 26. März:
---
- [x] Implemented the goal class better
- [x] Restructured the code for better readability

### 27. März:
---
- [x] Implemented the goal class completely
- [x] Implemented charging stations
- [x] First analysis of paths and coverage of heatmap
- [x] Implemented first analysis with emissions
- [x] And cost as well and a map to see where they are flying

### 3. April:
---
- [x] Implemented that if the intensity of the fire is below 0.5 it is deactivated
- [x] The logic seems to work, different values produce different results
- [x] Implemented the fire and stations effectively, can work on top of this, it's going in the right direction

### 8. April:
---
- [x] Asked DJI support for information regarding the drones
- [x] Implemented a weight/payload effect to the drones' emissions
    - [x] Better emission and resource analysis
- [x] Created a thing that analyzes the drones' performance and how it could be optimized

### 11. April:
---
- [x] Implemented the water charging better
- [x] Implemented the fire spreading

> Thoughts so far: I noticed that the fire was spreading faster than the drones could handle it, but from my analysis which I do from the model performance, I could gather that the limiting factor was always the energy --> so I added new recharge stations and now all the fires are getting extinguished faster than the model can run

- [x] Implemented comprehensive analysis
- [x] Implemented analyzing different parameters of the drone model to see which is the best set of parameters for the firefighting strategy

### 14. April:
---
- [x] Integrated a plane and runway class
- [x] Compared the two approaches
- [x] Also hybrid firefighting model

### 21. April:
---
- [x] Started the writing process
    - [x] Simulation explanation
    - [x] Importance of thesis
- [x] Making the code more readable
- [x] Working on the other pathfinding algorithms:
    - [x] Implemented the ACO algorithm --> Already noticeable that it is computationally much more complex but the movement seems more organic
        - [x] The ACO seems to be less effective because it moves more and therefore uses more energy and the drones can not recharge quick enough --> Increasing the number of drones seems to help
    - [x] Implemented the ABC algorithms
- [x] Implemented an analysis which compares the different pathfinding algorithms, tests their maximum capability

### 22. April:
---
- [x] Continued writing process: GOAL FOR THE END OF THIS WEEK: Finish first draft of thesis structure

### 23. April:
---

#### writing:
- [x] flow chart for drone logic / decision making
- Pathfinding alrogithms:
    - [ ] A* search explained
    - [ ] ABC explained
    - [ ] ACO explained
- Drone: 
 - [x] properties explained
 - [ ] functions explained
 - 
#### coding:
- [x] overworked the ABC and ACO algorithm and invcreasing the size of teh models (more ants and more bees) improved the model so much!!
- [x] idea of implementing a clustering algorithms for high risk fire areas
    - started implementing it with a Kmeans cluster: so far when comparing it does not improve the mdoe


### 24. April
---

- [x] progress on writing the first draft

### 25 april
---

- [x] more progress on the writing for travis. send it in for feedback

### 28 april
---

- [ ] cleaned up the structure of the notebook a bit ready for more developing soon

### 5 may
---
- [x] mermaid diagram optimization
- [ ] started comparative analysis run it for 1000 steps... 

### 6 may
---
- thesis meeting
- changed datacollection approach

### 7 May
---

- [x] compare emissions and cost for all approaches
- look why ACO is not working perfectly
- hybrid approach
- do the time complexity for the differnt pathfinding algorithms
- [x] emissions to make sense
- [x] annotated the drone agent

### 8 May
---
- [ ] annotate the rest of the code
- [ ] finish the Introduction section

### 9 May
---
- [ ] finish the related work session
- [ ] the cost and emisisons from the runway need to be adapted aswell


