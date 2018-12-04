# HW 4 Algorithms for Simple OpenAI Gym Environments

## Problem 1:

When the velocity is negative, I push the cart left. When the velocity is positive or 0, I push the cart right. This means that the cart is always being pushed in the direction of its velocity. That allows it to get maximum speed/momentum as quickly as possible, allowing it to go over the hill and reach the flag.


## Problem 2:

When the pole velocity at the tip is negative, the cart will go to the right. When the pole velocity is positive, the cart will go to the left. The simulation usually terminates when the cart hits the side of the window.


## Problem 3:

Used instructor's code as base. Changed state_size to 2 and action_size to 3. Removed the sleep. Tried many different reward policies to try to get it to work. Tried a reward that is based on the position and the velocity. Tried a reward that is based on the highest obtained positions. Tried a reward based on the highest obtained velocities. None of them work.

## Problem 4:

Wrote the answers to problem 4. Please see 04_algorithms_methods_overview.ipynb to read them.
