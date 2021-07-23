# Probability_Distributions Package

This package contains two types of probability distributions
1. Gaussian Distribution
	In probability theory, a normal (or Gaussian or Gauss or Laplace–Gauss) distribution is a type of continuous probability distribution for a real-valued random variable. The general form of its probability density function is

{\displaystyle f(x)={\frac {1}{\sigma {\sqrt {2\pi }}}}e^{-{\frac {1}{2}}\left({\frac {x-\mu }{\sigma }}\right)^{2}}}{\displaystyle f(x)={\frac {1}{\sigma {\sqrt {2\pi }}}}e^{-{\frac {1}{2}}\left({\frac {x-\mu }{\sigma }}\right)^{2}}}

	A normal distribution is sometimes informally called a bell curve. However, many other distributions are bell-shaped

2. Binomial Distribution 
	In probability theory and statistics, the binomial distribution with parameters n and p is the discrete probability distribution of the number of successes in a sequence of n independent experiments, each asking a yes–no question, and each with its own Boolean-valued outcome: success (with probability p) or failure (with probability q = 1 − p). A single success/failure experiment is also called a Bernoulli trial or Bernoulli experiment, and a sequence of outcomes is called a Bernoulli process; for a single trial, i.e., n = 1, the binomial distribution is a Bernoulli distribution. The binomial distribution is the basis for the popular binomial test of statistical significance

# FILES 

Binomialdistribuution.py : python file conatining the Binomial() class for binomial distribution related calculations. This file calculates the mean , standard deviation , performs addition of two distributions if they have the same value of p otherwise raises an exception . it also includes functions for pdf and plotting the probability distribution functions. For further info, look into the file itself for better understanding of the functions present.

Gaussiandistribution.py : python file containing Gaussian() class for gaussian or normal distribution related calculations. This file calculates the mean , standard deviation , performs addition of two distributions. This file asks the user to input whether the data is sample or a poplulation for calculation purposes .It also includes functions for pdf and plotting the probability distribution functions. For further info, look into the file itself for better understanding.For further info, loo into the file itself for better understnding of the functions present.

Generaldistributio.py : python file containing the Distributions class , that contains the function read_data_file() for raeding_data_files.

license.txt : MIT License.

# Installation

## Dependencies :

python(>=3.6)
matplotlib(>=3.4.2)

