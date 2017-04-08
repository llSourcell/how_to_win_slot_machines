# how_to_win_slot_machines
This is the code for "How to Do Win Slot Machines - Intro to Deep Learning #13' by Siraj Raval on YouTube

# Coding Challenge - Due Date - Thursday, April 13th at 12 PM PST

The coding challenge for this video is to use multiple slot machines instead of one. This way, state is taken into account. See this [article](https://getstream.io/blog/introduction-contextual-bandits/) for more info on this. Bonus points given for applying the code to a real world use case. You'll learn more about how policy and value functions are related in reinforcement learning by doing this exercise. 

## Overview

This is the code for [this](https://www.youtube.com/watch?v=AIeWLTUYLZQ) video on Youtube by Siraj Raval as part of the Udacity Intro to Deep Learning nanodegree. This code implements a technique called [policy gradients](http://www.scholarpedia.org/article/Policy_gradient_methods) to solve the [multi-armed bandit problem](https://en.wikipedia.org/wiki/Multi-armed_bandit). We use only 1 slot machine with 4 arms in this code and use an epsilon greedy policy to help select the best actions. Our agent is a simple 1 layer neural network built in tensorflow. 

## Dependencies

* tensorflow (https://www.tensorflow.org/install/)
* numpy

## Usage

Run `jupyter notebook` in the main directory of this repository in terminal to see the code pop up in your browser. 

Install jupyter [here](http://jupyter.readthedocs.io/en/latest/install.html) if you haven't already.

## Credits

The credits for this code go to [awjuliani](https://github.com/awjuliani). I've merely added a wrapper to get people started.

