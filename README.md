# PageRank

## Introduction

PageRank is an algorithm used to measure the importance of web pages based on the links between them. It was originally developed by Larry Page and Sergey Brin as part of their work on Google.

## How Does PageRank Work?

PageRank works on the idea that a page is important if other important pages link to it.

- Each page is represented as a node in a graph.
- Links between pages are represented as directed edges.
- Pages receive scores based on the number and importance of pages linking to them.
- The scores are calculated iteratively until they become stable.

## Damping Factor

The damping factor represents the probability that a user continues following links rather than jumping to a random page. A commonly used value is 0.85.

## Basic Formula

PR(A) = (1 - d) / N + d × Σ(PR(Tᵢ) / C(Tᵢ))

Where:

- PR(A) is the PageRank score of page A.
- d is the damping factor.
- N is the total number of pages.
- Tᵢ represents a page linking to A.
- C(Tᵢ) is the number of outgoing links from page Tᵢ.

## Applications

- Ranking web pages in search engines.
- Analyzing networks and relationships.
- Identifying influential nodes in a graph.

## Project Goal

This project explores the mathematical concepts behind the PageRank algorithm and how links influence the importance of nodes in a network.# Pagerank
