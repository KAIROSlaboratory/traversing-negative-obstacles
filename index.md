# Towards Fully Autonomous Negative Obstacle Traversal Via Imitation Learning Based Control
## June 13,2022
Current research in experimental robotics has had a focus on traditional, cost-based, 1
navigation methods. These methods ascribe a value of utility for occupying certain locations in the 2
environment. A path planning algorithm then uses this cost function to compute an optimal path 3
relative to obstacle positions based on proximity, visibility, and work efficiency. However, tuning 4
this function to induce more complex navigation behaviors in the robot is not straightforward. For 5
example, this cost-based scheme tends to be pessimistic when assigning traversal cost to negative 6
obstacles. Its often simpler to ascribe high traversal costs to costmap cells based on elevation. This 7
forces the planning algorithm to plan around uneven terrain rather than exploring techniques that 8
understand if and how to safely traverse through them. In this paper, imitation learning is applied to 9
the task of negative obstacle traversal with Unmanned Ground Vehicles (UGVs). Specifically, this 10
work introduces a novel point cloud-based state representation of the local terrain shape and employ 11
imitation learning to train a reactive motion controller for negative obstacle detection and traversal. 12
This method is compared to a classical motion planner that uses the dynamic window approach 13
(DWA) to assign traversal cost based on the terrain slope local to the robots current pose.
<p align="center">
<iframe width="560" height="315" src="https://www.youtube.com/embed/atwoEgyZkHo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</p>
