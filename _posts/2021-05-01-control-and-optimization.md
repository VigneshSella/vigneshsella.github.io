---
layout: post
title: Optimal control of quadcopters and robonauts
categories: [projects, miscellaneous]
excerpt: Developed real-time control systems for a simulated quadcopter and a two-wheeled robot, using a state-space dynamics representation, LQR, and hill-climbing algorithms to optimize performance
---

These two projects were part of the Control Systems and Optimizatin course as part of my undergraduate studies in aerospace engineering at the Univeristy of Illinois at Urbana-Chamapign. Both projects involved creating a real-time control system using a state-space representation of the dynamics of the system. To delve into optimal control we also implemented a linear-quadratic regulator (LQR). The weights and parameters of this system were up to us to optimize. The environment in which we tested our control systems was a simulated, limited-physics, with fixed time-step simulation setup in MATLAB. The first project was to bring a quadcopter from any (within reason) orientation to a fixed point in space, the reference location. We then had to minimize the error with respect to the reference location, and the time it took the system to arrive at this equilibrium. An example of the quadcopter in action can be seen in the GIF below,

![Quadcopter](/images/quadcopter.gif)

In the final project of the year we were tasked with guiding a "robo-naut" in a race on a twisting and turning track. The robot had to be able to navigate the track without going out of bounds, all the while keeping itself upright (it was on two wheels) in the least amount of time. The GIF below shows the robot navigating the track, 

![Robonaut](/images/robonaut.gif)

In order to train the weights for this system I used a hill-climbing algorithm, an iterative approach at finding the (local) optimum of a function. To avoid local optima, or at least hope for a result close to the global optimum, I used a random restart approach. This involved running the hill-climbing algorithm multiple times, each time with a different set of initial weights. The best result of all the runs was then chosen as the final result. A simple diagram to see the potential effect/advantage of this approach can be seen in the image below,

![Hill Climbing](/images/hill_climbing.png)


