# PINNs-Physics-informed-neural-networks

This repository contains the report and the corresponding codes of my research internship at Friedrich-Alexander-Universität Research Center for Mathematics of Data in Erlangen, Germany. The main goal of this work was the application of Physics-Informed Neural Networks (PINNs) to solve various forward and inverse problems in PDEs, where I take the well-understood 1 dimensional wave equation as an example for numerical experiment and error analysis. The codes are organized as follows: 

- all_together_loss_time.py: shows the test error-computational time dependency for different structures of neural networks.

- changing_nodes_test_loss.py: shows the test error-computational time dependency for neural network structures with different numbers of nodes

- control.py: solves the null controllability problem of the 1d wave equation

- first_case_no_damage.py: solves the degenerating 1d wave equation when $a(x)=4$

- second_case_damage.py: solves the degenerating 1d wave equation when $a(x)=8|x-0.5|$

- third_case_double_damage.py: solves the degenerating 1d wave equation when $a(x)=16|x-0.5|^2$

- inverse_problem.py: solves the inverse problem of the 1d wave equation

- test_loss_time.py: shows the test error-computational time dependency for a specific structure of neural network

- train_error_val_error_time.py: displays the train error/validation error/computational time-size of training set dependencies

- Wave_equation.py: solves the 1d wave equation

- Wave_equation_otherBC.py: solves the 1d wave equation with Neumann boundary conditions

- degenerate_wave.m: 
