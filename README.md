# Dynamic A Star Algorithm

[![build:passing](https://img.shields.io/badge/build-passing-bluevoilet.svg)](https://github.com/lkoshale/DA_STAR)
[![build:passing](https://img.shields.io/badge/Webpage-here-brightgreen.svg)](https://lkoshale.github.io/dynamic_a_star)

This repository contains elements for the [Website](https://lkoshale.github.io/dynamic_a_star)
C++/CUDA library of algorithm is published [here](https://github.com/lkoshale/DA_STAR) 

## About
A\* is one of the widely used path planning and shortest path approximation algorithms. It is applied in a diverse set of problems from path-finding in video games and robotics to codon optimization in genetics. In this work, we focus on A\* for graphs that are subjected to update operation, where an update operation refers to the insertion or deletion of an edge. Instead of performing A\* again from start each time graph is subject to update, our algorithm process the sub-graphs which are affected by the update. For temporal graph available at [SNAP](http://snap.stanford.edu/data) for 100 updates we got 25x-40x of performance improvement over repeated A* search. [More details](https://github.com/lkoshale/DA_STAR)

## Acknowledgement
Built using [reveal.js](https://github.com/hakimel/reveal.js)






