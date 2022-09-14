# Data-driven-Optimization-with-Neural-Networks
The code and the provided dataset are a companion to the paper titled "Using Neural Networks To Guide Data-Driven Operational Decisions".
The paper can be found here: https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4217092.
The code is provided in the form of a ipynb Python notebook. While it allows you to generate your own data, a data set is also provided in the form of a csv file. 
You can import the data, standardize and split it into train and vlidation sets and train a neural network with it.
Finally, after arriving at a trained neural network, for a given covariate value, you can compute the gradient of its prediction value with respect to the decision input, and optimize its prediction value.
The necessary packages are all imported in the code.
Please email saman.lagzi@rotman.utoronto.ca for correspondance regarding the project.

# A synopsis of our framework:
![Framework](https://user-images.githubusercontent.com/113304575/189544424-306c0d05-0c9e-49fe-8ef8-0e9c8aae6369.png)
