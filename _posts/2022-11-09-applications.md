---
layout: post
title: Applications Of Quantum Computing
subtitle: By Demi Lei
cover-img: assets/img/QML_diagram.png
thumbnail-img: assets/img/QML_diagram.png
share-img: assets/img/QML_diagram.png
---
**Why is Quantum Computing Important?**
<ul>
As things around us become increasingly digitized, the amount of data generated each day increases. Currently, we generate about 2.5 exabytes of data daily. On the other hand, our processing power on classical computers is predicted to be unable to keep up with the increasing quantities of data. Although Moore's Law predicted a doubling in computing capacity every two years, the increase in the computing capacity and speed of classical chips is inevitably slowing down as transistors approach the size of a silicon atom where problems such as quantum tunneling begin to arise. To keep up with Moore’s Law and be able to process the enormous amount of data generated every day, we will need a new solution that doesn’t require making transistors smaller and smaller; therefore, quantum computers (QC) are necessary for future development in technology. 
</ul>

**Why is Quantum Computing Powerful?**
<ul>
Although QC is still at an early stage of development and they are not precise enough for industrial application, we can still see immense potential in this technology. QC has an immense advantage over traditional computers because they use qubits instead of bits for operation. Bits can only be in discrete deterministic positions of 0 or 1; while qubits can also be in superposition - the state of simultaneously being in multiple positions with some probability to be at each of the positions. Since qubits can be in a continuous number of possible states, QC can perform an incredibly large amount of computations with a limited number of qubits - in general, the amount of information that can be processed by a QC with n qubits grows exponentially. Although QC isn't stable or precise enough for industry use, we can still foresee some promising applications in the near future. Some tasks that are difficult for classical computers are rather straightforward for QC, such as generating a truly random number or imitating a natural process. Such probabilistic tasks are perfect for qubits due to their non-deterministic nature and combined with QC's ability to process data in machine learning, quantum machine learning (QML) and quantum enhanced optimization (QEO) are becoming some of the more applicable ways of utilizing QC with the current technology.
</ul>

[![Classical Bit vs. Quantum Bit, or Qubit](https://raw.githubusercontent.com/dan-3lliott/theoreticalminimum/master/assets/img/bit_vs_qubit.jpeg)](https://news.fnal.gov/2021/04/new-computing-algorithms-expand-the-boundaries-of-a-quantum-future/)
Classical Bit vs. Quantum Bit, or Qubit

<ul>
Overall, classical computers are better at training models that are supervised in training, discriminative, deterministic, and parallelizable, due to their discrete nature. However, for QC, since a qubit can be in an infinite and continuous number of states, it has the ability to evaluate multiple states and compute multiple operations at the same time. Hence, QC has significant advantages over classical computers when dealing with unsupervised, generative, and probabilistic machine learning algorithms - algorithms that are difficult to compute on a GPU.
</ul>

**Examples of application of Quantum Computing - Quantum Machine Learning (QML)**
<ul>
Current QML and QEO are mostly hybrid quantum-classical computer algorithms - quantum-inspired optimization algorithms. QML and QEO are especially useful when dealing with high-dimensional datasets. In other words, if there are only a few variables (i.e. less than a hundred), classical computers with current algorithms are generally enough. But if the dimension gets large, the fact that qubits can be in multiple states at the same time is extremely helpful, therefore providing a speed-up for many current machine learning algorithms. Besides its ability to process high dimensional data, quantum-inspired machine learning is also another important contribution of quantum systems. For example, Kerenidis and Prakash’s quantum recommendation system is a quantum algorithm designed to generate personalized recommendations for individual users based on the past records of a group of users, such as purchases, views, or ratings. This algorithm is not only faster than all of the classical algorithms being used in the back-end of the websites we use on a daily basis, but its classical analog is also exponentially faster than other classical recommendation algorithms. Although this means that Kerendis and Prakash’s algorithm does not provide an exponential speed-up over the classical algorithm since it is proven to be a polynomial speed-up, it is still important to recognize QC and quantum algorithms and inspire researchers to develop faster machine learning algorithms for classical machines. 
</ul>

<ul>
In conclusion, although QC is still in its early stage of development, it is already providing us with many useful applications. QC is not only providing a new hardware haven for Moore’s Law but also inspiring growth in algorithm and complexity research for both quantum and classical computers. 
</ul>












