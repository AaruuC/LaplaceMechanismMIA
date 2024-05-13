# Visualization of Laplace Mechanism

## Dataset EDA
![image](https://github.com/AaruuC/LaplaceMechanismMIA/assets/85206941/4fa1b5af-954e-43c9-b360-64a400b287a9)

## Laplace Mechanism: Epsilon/Dataset Size vs. Total Error
![image](https://github.com/AaruuC/LaplaceMechanismMIA/assets/85206941/ff485e76-8cb1-470c-8388-4b00274a65ac)

## Membership Inference Attack: 
In an MIA, an attacker is provided with the following information: a dataset x; a dataset x’ that is identical to x except that it is missing one element of x (so if x is of length n, x’ is of length n-1); and a function f() that will be applied either to x or x’. More precisely, the attacker is given as input x and x’, and a value y that is the output of the LM on either f(x) or f(x’). In other words, y is either f(x) plus Laplace noise, or f(x’) plus Laplace noise. The goal of the MIA is to use x, x’ and y to guess/determine whether the input to the LM was f(x) or f(x’).
![image](https://github.com/AaruuC/LaplaceMechanismMIA/assets/85206941/7337cdc8-9422-4dc8-9c36-aecf574a0d6d)
