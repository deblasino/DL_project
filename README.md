# DL_project
Deep Learning's project created in Google Colab.

A sequence-to-sequence transformer trained from scratch to translate parenthesized arithmetic expressions into Reverse Polish Notation. Given ((c+a)*(d/(c/e))) it outputs ca+dce//*
It has to learn the tree structure of the expression from the token sequence alone, and then emit it in a different traversal order.
