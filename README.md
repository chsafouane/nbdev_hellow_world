nbdev_hellow_world
================

<!-- WARNING: THIS FILE WAS AUTOGENERATED! DO NOT EDIT! -->

A deck of cards demo of [nbdev](https://nbdev.fast.ai) based on ideas
from Allen Downey.

## Install

Install using:

``` sh
pip install nbdev_hellow_world
```

or

``` sh
conda install -c fastai nbdev-hellow-world
```

## How to use

This lib provides a
[`Card`](https://chsafouane.github.io/nbdev-hellow-world/card.html#card)class
you can use to create, display, and compare playing cards:

``` python
Card(1, 3)
```

    3♦️

Suits are numbered according to this list:

``` python
suits
```

    ['♣️', '♦️', '❤️', '♠️']

Ranks are numbered according to this list:

``` python
ranks
```

    [None, 'A', '2', '3', '4', '5', '6', '7', '8', '9', '10', 'J', 'Q', 'K']
