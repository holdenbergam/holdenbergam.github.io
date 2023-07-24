---
title: "Notes on Nonlinear Dimensionality Reduction"
collection: teaching
type: "Independent Studies"
permalink: /teaching/redux
venue: "Verma Lab, Columbia University"
date: 2023-05-10
location: "New York, NY"
---

I have been working on research in dimensionality reduction (specifically, a theoretical treatment of the famous t-distributed stochastic neighbor embedding, more commonly known as t-SNE). Here are some short pedagogical notes. 

Probably Approximate Johson-Lindenstrass Lemma
======
<a href="jl.pdf">[Notes] </a>
The Johnson-Lindenstrauss Lemma is a fundamental result in non-linear dimensionality reduction which shows that random projections of high-dimensional data happen to preserve pairwise distances. Usually this is formulated in terms of a lower bound on the number of dimensions we can project into. This lower bound is dependent on \(n\) (the number of points) and \(\epsilon\) (the tolerated amount of distortion in the embedding). In this writeup, we show a version of the lemma where the lower bound takes into account a user-provided \(\delta\) parameter, which specifies the probability with which a JL transform actually gives a good embedding.