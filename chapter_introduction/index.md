# Introduction

Bayesian optimization provides a unified framework that solves the problem ofsequential decision-making under uncertainty. It includes two key components: asurrogate model approximating the unknown black-box function with uncertaintyestimates and an acquisition function that guides the sequential search. This bookreviews both components, covering both theoretical introduction and practicalimplementation in Python, building on top of popular libraries such as GPyTorch andBoTorch. Besides, the book also provides case studies on using Bayesian optimizationto seek a simulated function's global optimum or locate the best hyperparameters (e.g.,learning rate) when training deep neural networks. The book assumes readers with aminimal understanding of model development and machine learning and targets thefollowing audiences:

* Students in the field of data science, machine learning, oroptimization-related fields
* Practitioners such as data scientists, both early and middle in theircareers, who build machine learning models with good-performinghyperparameters
* Hobbyists who are interested in Bayesian optimization as a globaloptimization technique to seek the optimal solution as fast aspossible

All source code used in this book can be downloaded fromgithub.com/apress/Bayesian-optimization.