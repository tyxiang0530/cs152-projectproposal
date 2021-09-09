# Comparing the Effectiveness of Reservoir Computing, Lagrangian Neural Networks, and Hamiltonian Neural Networks on the Forecasting of a Chaotic Double Pendulum!

## Project Description
This project seeks to compare the more general model of reservoir computing against the physics-specific architecture of Lagrangian and Hamiltonian Neural Networks. We will give each model the tasks of forecasting the motion over time of a double pendulum. We will then compare the performance of each model.

The double pendulum is a classic example of a chaotic system in physics. Slight alterations in the initial conditions of the system can lead to drastic changes in the path of the pendulum. This makes predicting the motion of the system by hand quite difficult without significant mathematical work.

![](https://github.com/tyxiang0530/tai152proposal.github.io/blob/main/images/Demonstrating_Chaos_with_a_Double_Pendulum.gif)

Reservoir computing has proven to be successful in the forecasting of chaotic systems and it may perform well on the task of forecasting the double pendulum's path. When fed a set of initial conditions and subsequent positions, it could be possible to train a model that is capable of accurately predicting the pendulum's motion. Lagrangian Neural Networks are useful for specific tasks involving the principle of least action, the Lagrangian, and can be trained to generate a Lagrangian (a function describing the differences between potential and kinetic energy) from a collection of data points. Hamiltonian Neural Networks perform the same function, but instead calculate the Hamiltonian (a function describing the sum of kinetic and potential energies) from the set of points. The double pendulum's Lagrangian and Hamiltonian can both be used to generate its path over time.

This project serves as a means to compare a more general approach (Reservoir Computing) to two physics-specific approaches (Hamiltonian NN and Lagrangian NN), and also provides insight into the effectiveness of fitting a Hamiltonian and Lagrangian on the same task.

Datasets for the initial conditions of a double pendulum and its subsequent motion are available and also can be created. The Pomona Physics department can provide a double pendulum video setup and also has a program that is capable of mapping the paths of each individual pendulum over time, and thus additional data can be easily generated.

## Goals: 
Learn more about Reservoir Computing, Hamiltonian Neural Networks and Lagrangian Neural Networks

Compare the effectiveness of general and physics specific models on forecasting the motion of a double pendulum (a chaotic system)
