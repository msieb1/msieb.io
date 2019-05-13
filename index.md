## Maximilian Sieb

Hello! I am Max and a 2nd year student within the MSR program at the Robotics Institute at Carnegie Mellon University, where I am glad to be co-advised by Prof. Katerina Fragkiadaki & Prof. Oliver Kroemer.

My research is motivated by enabling robots to learn complex skills by leveraging human demonstrations. I mostly focus on visual imitation learning and model-based reinforcement learning.

### Selected Projects

#### Probabilistic Trajectory Segmentation by Means of Hierarchical Dirichlet Process Switching Linear Dynamical Systems

This project is about inferring dynamical modes of a given trajectory in a non-parametric fashion. Simply said, the algorithm tries to fit multiple linear segments within the trajectory where the number of fitted segments does not have to specified, but is inferred as well by using a non-parametric dirichlet prior.

[Link to Repo](https://github.com/msieb1/switching-linear-dynamical-systems)

[Link to PDF](pdf/HDP_SLDS.pdf)

#### Bachelor Thesis: Design and Analysis of a Ball-Balancing Plate

This thesis revolves around the design of a ball-balancing plate and the anaylsis & implementation of different control algorithms. The thesis describes the entire design process: The CAD-design of the contraption, the dynamical & mechanical analysis, the control design & analysis, the microcontroller implementation, and experimental verification.

[Link to PDF](pdf/bachelor_thesis.pdf)
      



### Publications

[Data Dreaming for Object Detection: Learning Object-Centric State Representations for Visual Imitation](pdf/ddfod.pdf) 

In this paper, we show how we can use synthetically generated image data from only a few background-subtracted ground-truth images to build instance-specific object detectors robust to partial occlusions. Further, we demonstrate how we can use these detectors to imitate human demonstrations of manipulation tasks in a sample-efficient manner, where the overall imitation learning process takes less than 10 minutes.

[Visual Entity Graphs for Structured Visual Imitation](https://msieb1.github.io/visual-entity-graphs/)

In this paper, we propose a graph-structured state representation for visual imitation learning. We show we can use different visual entities of various granularities to obtain a state representation that can be used for reinforcement learning to learn manipulation skills within a few minutes of real-life policy rollouts.
