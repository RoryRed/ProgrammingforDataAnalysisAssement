Explain the overall use of the package ?
Numpy.random creates pseudo random numbers.
This stems from the fact that it is used as part of a calculation.It is only pseudo random and not true random due to the fact that the number is calculated from an algorithim.
This leads pseduo random numbers being less useful for security as any random number created from an algorithim can be calculated directly from the same algorithim.[1]
Any simulation of real life events require a random number to be generated[2].Random sampling is vital for seeing the true effects of data and the accuracy of the data[3]
The numpy.random package creates predictable arrays which allowes the data to be compared on an appropriate level.

Explain the use of sample random data and permutation function.The permutation package allows for the reordering of an array

Simple random data 
rand(d0, d1, …, dn)	Random values in a given shape.
randn(d0, d1, …, dn)	Return a sample (or samples) from the “standard normal” distribution.
randint(low[, high, size, dtype])	Return random integers from low (inclusive) to high (exclusive).
random_integers(low[, high, size])	Random integers of type np.int between low and high, inclusive.
random_sample([size])	Return random floats in the half-open interval [0.0, 1.0).
random([size])	Return random floats in the half-open interval [0.0, 1.0).
ranf([size])	Return random floats in the half-open interval [0.0, 1.0).
sample([size])	Return random floats in the half-open interval [0.0, 1.0).
choice(a[, size, replace, p])	Generates a random sample from a given 1-D array
bytes(length)	Return random bytes. [7]

The uses of simple random data in this exercise have benn used to explain some of the simple random data in a more user friendly way
The permutations examined where the  numpy.random.shuffle and numpy.random.permintation

#Set seed 
Gives predictable measureable results for each seed this is shown that when the seed is called and gives the same result when each line of code is run. [4]

#Distrubustion 
examined where 
1 numpy.random.exeponetial
2 numpy.random.logistic
3 numpy.random.standard_normal
4 numpy.random.poisson
5
#Not called seed 
a random seed was selected but not called this was demonstarted by comparing it to called seed when called in the previous example  
selected a seed makes a predicable set of number for each which underlines the pseudo random nature of the seed.This shows how for security reason this form of random number generation can be predicted 





























[1]https://www.w3schools.com/python/numpy_random.asp
[2]https://subscription.packtpub.com/book/big_data_and_business_intelligence/9781785285110/2/ch02lvl1sec16/numpy-random-numbers#:~:text=An%20important%20part%20of%20any,Twister%2C%20to%20generate%20pseudorandom%20numbers.
[3]https://chrisalbon.com/python/basics/generating_random_numbers_with_numpy/
[4]https://stackoverflow.com/questions/21494489/what-does-numpy-random-seed0-do
[5]https://www.geeksforgeeks.org/random-sampling-in-numpy-randint-function/
[6]https://het.as.utexas.edu/HET/Software/Numpy/reference/generated/numpy.random.randint.html
[7]https://docs.scipy.org/doc/numpy-1.15.0/reference/routines.random.html