# Advent of Code 2020

Everyone's doing it... another year of Advent of Code!

## Structure

- Every day is a directory
- There is also a shared namespace/module `advent` to share solutions

## Answer list

- [Hello, world!](00/)
- [Day 1](01/)

## Language and approach

I have selected Lua because:

* It isn't Javascript nor Python
* It has little or no standard library
* It's embeddable into just about everything
* Everything is a table

The metagoal is to develop my own Lua "mini standard library" like one might
have done 30 years ago, like in C\+\+ before the STL.

## Advents of Code Past

I was stuck trying to figure out the closed form soulution for converting between a number spiral (like an Ulam sprial) and a vector or complex number, which would yield the Manhattan distance, e.g.

| []() | | | |
|:-:|:-:|:-:|:-:|
|   5 &rarr; -1+i   |    4 &rarr; i   |   3 &rarr; 1+i  | ... |
|   6 &rarr; -1   |    1 &rarr; 0   |   2 &rarr; 1 | ... |
|   7 &rarr; -1-i   |    8 &rarr; -1   |   9 &rarr; 1-i  | 10 &rarr; 2-i |
