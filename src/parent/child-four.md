---
title: Char Adjacency Matrix
---
###[Link to project on github](https://github.com/GrantHiggins16/Char-Bit-Manipulation-Adjacency-Matrix-)
In C++, a bool is 8 bits. This means that an adjacency matrix of size n by m takes up a space of (8nm) bits. A more efficient way of storing an adjacency matrix then is to create a matrix of chars. Each of these chars are, in a 64-bit system, 8 bits long just like a bool. However, these chars can have their individual bits manipulated so that they can represent 8 different values within the matrix. This means a matrix of size n by m takes up a space of (nm) bits. This project is an implementation of the above idea, an adjacency matrix made of chars.
