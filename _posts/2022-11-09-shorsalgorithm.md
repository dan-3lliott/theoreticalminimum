---
layout: post
title: A Brief History of Shor's Algorithm
subtitle: By Sarah Heyrman
cover-img: /assets/img/path.jpg
thumbnail-img: /assets/img/thumb.png
share-img: /assets/img/path.jpg
---

Who is Peter Shor?

Peter Shor is a professor of applied mathematics at MIT. He specializes in theoretical computer science: algorithms, computational geometry, combinatorics, and probability theory.
Shor’s current research is in quantum computing and quantum information theory. He is best known for his 1994 discovery of Shor’s algorithm, a quantum algorithm for prime factorization and discrete logarithms (Shor, “Peter Shor”). 

How Shor’s algorithm came to be

	Shor’s algorithm did not start with factorization. At a 1992 conference at Bell Labs, Shor attended a talk about the Bernstein-Vazirani algorithm; according to Umesh Vazirani, the algorithm ran faster on a quantum computer than it would on a classical computer. Shor, however, believed he could find a more convincing quantum algorithm. He took inspiration from Simon’s problem, where one must find the period, given a function only accessible as an oracle (or black box). Shor had initially rejected Simon’s paper when he was on the programming committee. This time, he used some of Simon’s logic and the Fourier transform (to find the period) on a quantum computer over an exponentially large period (Qiskit). Shor then applied his findings to solve discrete logarithms and wrote a paper, Polynomial-Time Algorithms for Prime Factorization and Discrete Logarithms on a Quantum Computer (Shor, “Papers Available Electronically”). A few days after giving a talk about discrete logs, he solved the factoring problem. Like Simon’s problem, factoring is very simple with small numbers but the difficulty scales quickly as the numbers get larger. Using classical computers, factoring numbers with a thousand or more digits is practically impossible (Qiskit). The world record for classical algorithms is 232 digits in about 2,000 CPU years. Shor’s algorithm, however, has changed what problems are considered possible using quantum computers (“Shor’s algorithm”).

Why does Shor’s algorithm matter?

Shor’s algorithm could break the RSA cryptosystem (The Jupyter Book Community). RSA is commonly used for banking, online shopping, authenticating messages, and many other important tasks (“RSA Encryption: Definition”). The algorithm relies on the fact that large integers are very difficult to factorize, yet easy to multiply (“RSA Encryption”). As an asymmetric cryptography algorithm, RSA uses two keys, one public (given to everyone) and one private. The public key is created by multiplying two large prime numbers. The same prime numbers are used to generate the private key.  The strength of encryption scales exponentially with the key size (“RSA Algorithm in Cryptography”). The general process is simple: a client requests data from a server, the server encrypts the data with the client’s public key and sends it back, then the client receives the data and decrypts it with their private key (Educative Answers Team). This cryptosystem can be hacked in a few ways: factoring, brute force attacks, the Euclidean algorithm, or hardware manipulation (RSA Encryption). On a large enough quantum computer (around 4000 error-corrected qubits), Shor’s algorithm could factor any public key to find the private key and access the encrypted data (Herman). The current largest quantum processor is the IBM Eagle, with 127 qubits, meaning RSA is safe for now (Chow et al.). At the rate quantum technology is evolving, however, RSA will need to be replaced in the near future. The new cryptosystem needs to be quantum-proof, accessible, and widely implemented when that time comes– at the moment, there is no obvious replacement. If this problem is neglected, RSA-encrypted information such as passwords, financial details, and emails could become vulnerable to attack, leading to a cybersecurity crisis that would affect nearly everyone (Herman). 
