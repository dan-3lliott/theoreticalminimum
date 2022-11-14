---
layout: post
title: Current Limitations of Quantum Computing
subtitle: By Daniel Elliott
cover-img: /assets/img/chipwide.jpg
thumbnail-img: /assets/img/chipthumb.jpg
share-img: /assets/img/atomcomputing.jpg
---

For many, the words “quantum computing” immediately evoke a mental image of sci-fi-esque circuitry, perhaps arranged in a radially symmetric fashion amongst several circular levels, being silhouetted against a black background with purple, blue, and orange highlights streaking throughout its many complex subsystems… such is the effect of the sensationalism which currently surrounds the quantum computing industry as a whole. Chances are, you’ve probably seen headlines such as “The Quantum Age Is Almost Upon Us and We Need to Start Taking It Seriously,” “How Quantum Computing Could Change The World,” or even “Why Quantum Computing Is Even More Dangerous Than Artificial Intelligence,” and you’ve likely wondered if there is any basis for such zealous claims. Truthfully, though some of the prospective technologies currently being developed in this domain do in fact have potential to revolutionize certain aspects of computing, there are still many significant limitations of application and progression which those working to develop such technologies must either embrace or overcome. This article will provide a high-level overview of the most significant challenges and limitations which researchers and scientists in the field of quantum computing face at present.

Firstly, though quantum computers have the ability to perform a few specific tasks and algorithms in a remarkably efficient manner, for most applications, they outclass classical computers by only a small margin. Since the manner in which quantum computers perform calculations is vastly different from their classical counterparts, new algorithms must be developed and additional steps taken to accomplish the same task; as such, in many circumstances, the use of a quantum algorithm is disadvantageous in comparison to its equivalent classical alternative. Sometimes, this leads to a significant “quantum advantage,” as is the case with the current fastest-known quantum algorithm for factoring integers, known as “Shor’s algorithm.” This is a prime example of an instance wherein quantum computers not only outperform their classical predecessors, but also one with markedly profound application to the real world. Readers who are familiar with digital encryption methods, particularly “public-key cryptography,” will remember that absurdly large integers are used as “keys” to keep transmitted data safe and secure as it makes its way from sender to recipient, as would be the case with most financial transactions taking place digitally. In some instances, Shor’s algorithm could be used to factor the integers representative of the data in question without having prior knowledge of the associated keys, thus decrypting whatever communication or transaction had taken place. In this application, the advantage of quantum computing is quite obvious; however, this kind of algorithmic supremacy is not yet universal for all commonly used quantum algorithms.

Secondly, quantum computers suffer from a unique issue known as quantum decoherence. Though more complex explanations can be found elsewhere, in brief, decoherence can be viewed as the loss of information from the quantum system into its environment, somewhat reminiscent of how energy in the form of heat will gradually flow out of a system into its surroundings in pursuit of thermal equilibrium. To combat this, quantum error correction measurements must be implemented, often in the form of a redundant system which stores multiple instances of the same information, thus allowing for later decoding and analysis through a “majority vote.” This intuitive albeit inefficient method ensures a relatively high degree of accuracy, even if error stemming from quantum decoherence or noise has somehow altered the stored information from its original state. Error correction methods, such as the above “repetition code,” are constantly being developed and evolved as a necessary means by which this inherent issue of quantum error may be addressed and hopefully overcome; unfortunately, for the time being, it still remains a very real issue with which those engaged in quantum-computing-related research must regularly grapple.

Thirdly, quantum computers require a very specific set of physical conditions to run properly, particularly when it comes to the range of temperatures within which they must operate. For example, superconducting quantum computer chips (such as those currently being used in research by organizations such as Google, IBM, and the like) must be kept as close to absolute zero (−273.15 °C, −459.67 °F) as possible; otherwise, noise, decoherence, and error will abound as a result of the thermal energy being introduced into the system. 

[![Vacuum-based cooling system currently in use by Atom Computing, a quantum computing company based in Berkeley, CA.](https://github.com/dan-3lliott/theoreticalminimum/blob/master/assets/img/atomcomputing.jpg?raw=true)](https://www.reuters.com/technology/atom-computing-invest-100-mln-colorado-quantum-computer-center-2022-09-28/)
Vacuum-based cooling system currently in use by Atom Computing, a quantum computing company based in Berkeley, CA. (Lee)

Currently, researchers make use of vacuums and specialized supercooling refrigeration systems to keep their chips cool, which unfortunately lack the ability to resist significant heat generation despite their remarkable ability to initially lower the temperature to such an extreme level. As such, when chips are utilized to run algorithms or perform calculations, the heat they invariably produce often leads to increased error, as explained above. Although future developments with regards to supercooling are on the horizon, they’re unlikely to make a significant impact, meaning that researchers must continue to deal with this frustrating constraint for the foreseeable future.

In closing, though quantum computing does have the potential to revolutionize the way in which certain computationally-dependent processes are carried out, there are still many hurdles to be overcome before this novel technology can truly leave its mark on modern society. However, the sheer amount of financial backing currently being received by organizations performing work in this sector, consisting of multi-billion-dollar grants and investments by individuals and governments the world over, reflects the contingent interest that humanity has in its development. Will we see quantum computing advance to the oft-discussed standard of “quantum superiority” within the next ten years? Such is unlikely; however, disregarding its developmental time frame and current limitations, the potential impact of quantum computing technologies cannot be disputed.













