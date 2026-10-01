# MASGroupProject1

# ♟️ Rook Polynomials and Chess

A computational exploration of **rook polynomials and combinatorial problems in chess**, developed as a group project by **Kaustav Choubey, Barbara Taraska, and James** during the first year of our BSc Mathematics degree.

The project combines combinatorics with programming to investigate chessboard configurations and related counting problems.

## 🔢 Rook Polynomial Calculator

The main part of the project is a program that computes the **rook polynomial of an arbitrary board**, including boards containing blocked squares.

For a board \(B\), let \(r_k\) be the number of ways of placing \(k\) mutually non-attacking rooks on its available squares. The rook polynomial is

\[
R_B(x)=\sum_{k\geq0}r_kx^k.
\]

We represent the board as a binary matrix and use **matrix permanents and recursively generated submatrices** to compute the coefficients \(r_k\).

This allows rook polynomials to be calculated computationally for general board configurations rather than only for a standard chessboard.

## ♜ Checkmate-in-One Program

We also built a program for a specific chess endgame problem involving **two rooks and a king**.

Given the locations of the three pieces, the program:

- determines whether the king is already checkmated;
- if not, searches for whether the rooks can deliver **checkmate in one move**.

Rather than attempting to implement a general-purpose chess engine, this component focuses on solving one well-defined chess problem algorithmically.

## 🧩 Further Explorations

The project also investigates several related questions arising from chess and discrete mathematics:

- attacking and non-attacking configurations of other chess pieces;
- probabilities associated with random piece configurations;
- generalisations of chessboard configurations to **higher dimensions**;
- the **Knight's Tour** and a backtracking approach to finding tours;
- an introduction to the mathematics and algorithms underlying chess engines.

## 💻 Project Website

The project was developed as an interactive website combining mathematical explanations, visualisations, and computational demonstrations.

The source code and accompanying material are contained in this repository.

## 👥 Contributors

**Kaustav Choubey · Barbara Taraska · James**

*BSc Mathematics — Year 1 Group Project*
