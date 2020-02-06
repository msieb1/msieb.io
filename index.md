## Hello!
I am Max, and I am currently working on computer vision and reinforcement & imitation learning for robot manipulation at *Covariant*.
I recently graduated from the MSR program at the Robotics Institute at Carnegie Mellon University, where I was glad to have been co-advised by Prof. Katerina Fragkiadaki & Prof. Oliver Kroemer. 


My research is motivated by enabling robots to learn complex skills by leveraging computer vision & human demonstrations. I mostly focus on visual imitation learning and model-based reinforcement learning.

### Publications
#### [Graph-Structured Visual Imitation](https://msieb1.github.io/visual-entity-graphs/)
*to appear in Conference on Robot Learning, 2019*
In this [paper](https://arxiv.org/pdf/1907.05518), we propose a graph-structured state representation for visual imitation learning. We show we can use different visual entities of various granularities to obtain a state representation that can be used for reinforcement learning to learn manipulation skills within a few minutes of real-life policy rollouts.
![](assets/graph-2.png)

#### [Data Dreaming for Object Detection: Learning Object-Centric State Representations for Visual Imitation](https://ieeexplore.ieee.org/document/8625007) 
*IEEE-RAS 18th International Conference on Humanoid Robots (Humanoids)*

In this paper, we show how we can use synthetically generated image data from only a few background-subtracted ground-truth images to build instance-specific object detectors robust to partial occlusions. Further, we demonstrate how we can use these detectors to imitate human demonstrations of manipulation tasks in a sample-efficient manner, where the overall imitation learning process takes less than 10 minutes.
![](assets/data_dreaming.png)


### Selected Projects
#### [Master Thesis: Visual Imitation Learning for Robot Manipulation](pdf/MSR_thesis_final.pdf)

I have recently obtained my Master's degree in Robotics, and my Master's thesis on Visual Imitation Learning for Robot Manipulation can be found on the official CMU website via [this]( https://www.ri.cmu.edu/publications/visual-imitation-learning-for-robot-manipulation/) link.
![](assets/master_thesis_vis.png)

#### [Probabilistic Trajectory Segmentation by Means of Hierarchical Dirichlet Process Switching Linear Dynamical Systems](pdf/HDP_SLDS.pdf)

This project is about inferring dynamical modes of a given trajectory in a non-parametric fashion. Simply said, the algorithm tries to fit multiple linear segments within the trajectory where the number of fitted segments does not have to specified, but is inferred as well by using a non-parametric dirichlet prior([repo](https://github.com/msieb1/switching-linear-dynamical-systems)).
![](assets/segmentation.png)

#### [Aligning Word Embeddings of Different Languages within a Shared Embedding Space](pdf/aligning-word-embeddings.pdf)
Learning translations between different languages has drawn a lot of focus recently. In this work, we examined how we can leverage shared embedding spaces of different languages to learn better translations overall. Do multilingual people "think" by subconsciously translating each language into a common embedding space, or is each language pair individually translated, i.e., our mind has a set dictionary for each translation pair? This project is motivated by this line of thinking: the key reasoning here is that different language translations could be thought of operating in an embedding space in which all languages can be embedded to some extent. Ideally, this would improve translation between language pairs by leveraging knowledge of multiple dictionaries which is encoded in the shared embedding space. 
![](assets/aligning.png)
      
#### [Bachelor Thesis: Design and Analysis of a Ball-Balancing Plate](pdf/bachelor_thesis.pdf)

This thesis revolves around the design of a ball-balancing plate and the anaylsis & implementation of different control algorithms. The thesis describes the entire design process: The CAD-design of the contraption, the dynamical & mechanical analysis, the control design & analysis, the microcontroller implementation, and experimental verification.
![](assets/bachelor_thesis_vis.png)
