---
layout: page
title: Research
permalink: /research/
nav: true
nav_order: 2
---

During my undergraduate studies, I have explored several topics at the intersection of physics, the life sciences, and neuroscience. Some of these interests have developed into research projects under the guidance of mentors, while others are questions I have explored by reading the literature.

## **Topic 1: Physical Principles of Sensing and Behavior**

How does a sensing and behavior system operate when an organism faces a complex and fluctuating environment, whether the organism is a single bacterium or a fruit fly, mouse, or human? Are there basic physical principles shared by these systems? This was the first question that drew me toward biophysics. Some of the earliest work I encountered was the research of Yuhai Tu, Howard Berg, and their collaborators on the Che system in *E. coli* chemotaxis, including [Mello and Tu (2003)](https://doi.org/10.1073/pnas.1330839100) and [Tu, Shimizu, and Berg (2008)](https://doi.org/10.1073/pnas.0807569105).

##### Project I: Building an Agent Based Model to Study the Environmental Adaptability of Sessile/Motile State Switching Strategies in *Bacillus subtilis*

Under the guidance of [Prof. Chao Tang](https://cqb.pku.edu.cn/tanglab/index.htm) at Peking University, I built an agent based model to study how switching between sessile and motile states helps *Bacillus subtilis* adapt to changing environments. The model builds on experiments by Dr. Zihan Li that measured how environmental conditions regulate switching rates between these states across a range of steady environments. I extended this setting to dynamic environments and performed computational simulations. Using information theoretic measures such as transfer entropy, I compared agents whose switching was regulated in both directions with agents for which only the motile to sessile transition was regulated. The aim was to quantify how much environmental information each strategy used in making decisions and to evaluate its adaptive value.

##### Project II: Using a Function Driven Optimization Model to Study the Coding Principles of the *Drosophila* Olfactory Circuit in the Dual Tasks of Gas Motion Sensing and Gradient Sensing

Under the guidance of [Prof. Thierry Emonet](https://emonet.biology.yale.edu/) and [Dr. Kevin Chen](https://kschen.scholar.princeton.edu/bio) at Yale University, I extended a recently reported circuit for odor motion sensing in *Drosophila* into a parameterized network that can be optimized. I designed a joint task that requires the network to sense both odor motion and odor gradients under a metabolic constraint. I then evaluated task performance, optimized the network parameters, and studied how a single parameter set balances these two forms of olfactory computation.

---

## **Topic 2: Physical Principles of Learning**

From adaptation in active matter to reinforcement learning in agents and the training of neural networks, learning is one route through which complex structures, functions, and behaviors emerge in biological and artificial systems. What are the dynamics of learning? To what extent can biological learning and machine learning be described within a common framework? How is learning connected to behavior? These questions are broad and difficult, but I find them especially compelling.

##### Project III: Dynamics and Renormalization Analysis of the Emergence of Low Rank Structure in Artificial Neural Networks

Low rank structure in parameter space and along learning trajectories has been observed in both biological and artificial neural networks. Under the guidance of [Prof. Yuhai Tu](https://users.flatironinstitute.org/~ytu10/) and Dr. Yikuan Zhang, I trained multilayer perceptrons and related networks on MNIST. I studied the stages through which low rank structure emerges by recording representations throughout training, rescaling network width, and applying regularization to intermediate singular values. I am interested in how these dynamics change with network scale and learning rate, and whether they admit a useful renormalization description.

---

## **Topic 3: Statistical Physics of Neural Networks**

Biological neural networks combine organization across many scales with high complexity, low energy consumption, and efficient coding. Inspired by the work of [William Bialek](https://phy.princeton.edu/people/william-bialek), [Christopher Lynn](https://physics.yale.edu/profile/christopher-lynn), and others, I am interested in several debated but intriguing ideas from statistical physics, including renormalization in neural activity, sparse coding, and stochastic thermodynamics. I am currently surveying the literature on these questions.
