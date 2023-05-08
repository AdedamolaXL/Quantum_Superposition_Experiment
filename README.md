# Quantum_Superposition_Experiment
An exploration of superposition behaviour in rolled dice as observed from a video camera


## INTRODUCTION
Quantum mechanics is a theory that relies heavily on probability, meaning that many of its predictions are based on statistical data. To help make sense of this, scientists have used the idea of statistical ensembles, which refers to different theoretical versions of the same system that may exist in different states. 
For instance, a state vector |ψ⟩ doesn't describe the state of a single system, but rather an abstract concept known as an ensemble. An ensemble refers to multiple identical copies of the same system, each of which may be in a different state. 

Let's look at some expressions that describe the state of a quantum system: 

 * The expression, |ψ⟩ = n∑i=1 αi|ai⟩, is a way to represent the state of a quantum system. It involves a sum over the different possible states of the system, represented by the basis vectors |ai⟩. The coefficients αi are complex numbers that represent the amplitude of the system being in the corresponding state |ai⟩. 

 * The expression n∑i=1 |αi|2 = 1 ensures that the total probability of finding the system in any state is equal to 1, meaning that the system must be in one of the possible states at any given time.

In quantum mechanics, when experimenters measure a physical quantity on a quantum system in a laboratory, they repeat the same experiment a large number of times on identically prepared systems. By doing so, they can calculate probabilities as limits of the relative frequencies of outcomes. This approach allows experimenters to statistically analyze the behavior of quantum systems and make predictions about their future states based on the probabilities of various outcomes.

### What is the fundamental difference between the probabilities delivered by the experiment consisting in rolling a die and those delivered by a typical quantum measurement? 

Rolling a die is a common example of a probabilistic experiment. To find the probability, denoted by P(i), of rolling a number i that is in the set {1, 2, 3, 4, 5, 6}, we can use Laplace’s classical definition of probabilities. This definition involves calculating the ratio of favorable cases to all possible cases. If we have a fair die with six faces, then P(i) for any i in the set {1, 2, 3, 4, 5, 6} is 1/6. 

Let's begin by noting that a die, when rolled, is a single entity that we can understand completely. In other words, we cannot assign hidden variables to the die's state that would allow us to predict the outcome without using probabilities. Even if we know the die's exact state before rolling it, such as the face that is currently on top and its position, this knowledge will not help us predict the final outcome of the roll when the die is thrown on the table.

The reason for this is that the primary cause of unpredictability in the experiment is not due to our lack of knowledge about the die's initial state, which we can assume to be completely known. Instead, it is due to the specific interaction between the die and the hand that throws it, as well as between the die and the surface on which it rolls before coming to rest with a final face showing. In other words, if we were to talk about hidden variables, they would have to be associated with the rolling experiment itself, rather than the initial state of the die

Thus the e very process of measurement (observation) creates the property which is measured, i.e., it is the very measurement that actualizes the property which, prior to the measurement, was only existing in potential terms {the potential terms here beig the 6 faces of the die). 

It's important to recognize that the actualization of potential elements of reality is a characteristic feature of quantum systems, and this leads to non-classical properties that can create interference effects. This suggests that many of the "strange" aspects of quantum physics are actually present in the examination of conventional examples used to demonstrate classical probability calculations since the origin of probability theory. We only need to view these examples as physical experiments assessing particular features or measuring specific observables.

This right here is the source of our theses, that and a lack of access to quantum precision instrumentation :)


### METHODOLOGY

*Materials:*
 
 * One die with six sides
 * Flat surface to roll the die on
 * Camera to record the experiment 
 * Noteboo to record the results

*Procedure:*

 * Choose a flat surface to roll the die on. Ensure that the surface is level and free from any potential sources of disturbance.
 * Prepare the die by ensuring that it is clean and free from any obstructions that may prevent it from rolling smoothly.
 * Begin the experiment by setting a timer to a fixed duration.
 * At regular intervals, in this case every 10 seconds, roll the die onto the flat surface. Record the result of each roll on a data sheet.
 * Repeat step 4, to conduct more rolls

*Expected scenario:*

For the purpose of this experiment, we are recording the *front face(s)* of the die, which the camera allows us to do due to the 180 degree view. In our experiment, a roll has two possible initial outcomes; one in which *one face* is recorded and the other in which *two faces* are recorded.


*Constructing an Hilbert Space*

Let's start with the 6-dimensional complex vector space for the case where the camera captures only one face of the die. We can denote the six possible outcomes as:

|1>, |2>, |3>, |4>, |5>, |6>

and the corresponding basis vectors in the Hilbert space as:

e_1 = [1, 0, 0, 0, 0, 0]
e_2 = [0, 1, 0, 0, 0, 0]
e_3 = [0, 0, 1, 0, 0, 0]
e_4 = [0, 0, 0, 1, 0, 0]
e_5 = [0, 0, 0, 0, 1, 0]
e_6 = [0, 0, 0, 0, 0, 1]

The complex vectors in this 6-dimensional Hilbert space can be represented as linear combinations of these basis vectors.

Now let's move on to the 36-dimensional complex vector space for the case where the camera captures two faces of the die. We can denote the 36 possible outcomes as:

|1,1>, |1,2>, ..., |1,6>, |2,1>, |2,2>, ..., |6,6>

Here, the state |i,j⟩ represents the outcome where the first face of the die shows i and the second face of the die shows j. This gives us a total of 36 basis states.

The corresponding basis vectors in the Hilbert space can be denoted as:

e_1 = [1, 0, 0, ..., 0, 0]
e_2 = [0, 1, 0, ..., 0, 0]
...
e_36 = [0, 0, 0, ..., 0, 1]

The complex vectors in this 36-dimensional Hilbert space can be represented as linear combinations of these basis vectors.
      
To make predictions about the outcomes of measurements for this operator, we need to apply it to a state vector representing the quantum state of the die.

Let's say we start with an initial state vector of:

psi = [0, 0, 0, 0, 0, 1]

which represents the state where the die is in state 6 (the last entry in the vector) and no measurement has been made yet.

*Calculating the probability of a particular outcome*

 A. 
The measurement operator for the outcome of rolling a die and the camera capturing only one face can be represented by the matrix:

M = [[1, 0, 0, 0, 0, 0],
     [0, 1, 0, 0, 0, 0],
     [0, 0, 1, 0, 0, 0],
     [0, 0, 0, 1, 0, 0],
     [0, 0, 0, 0, 1, 0],
     [0, 0, 0, 0, 0, 1]]
     
To make predictions about the outcomes of measurements, we need to calculate the probability of each outcome. Let's assume that the die is initially in the state:

|psi> = (1/sqrt(6)) * [1, 1, 1, 1, 1, 1]

This is a uniform distribution over all possible outcomes, since the probability of each outcome is the same.

To calculate the probability of obtaining a certain outcome, we can use the formula:
p_i = |<e_i|psi>|^2

where e_i is the ith basis vector and |<e_i|psi>|^2 is the squared magnitude of the inner product between e_i and |psi>.

Using this formula, we can calculate the probability of obtaining each outcome:
 * p_1 = |<e_1|psi>|^2 = |(1/sqrt(6)) * [1, 0, 0, 0, 0, 0]|^2 = 1/6
 * p_2 = |<e_2|psi>|^2 = |(1/sqrt(6)) * [0, 1, 0, 0, 0, 0]|^2 = 1/6
 * p_3 = |<e_3|psi>|^2 = |(1/sqrt(6)) * [0, 0, 1, 0, 0, 0]|^2 = 1/6
 * p_4 = |<e_4|psi>|^2 = |(1/sqrt(6)) * [0, 0, 0, 1, 0, 0]|^2 = 1/6
 * p_5 = |<e_5|psi>|^2 = |(1/sqrt(6)) * [0, 0, 0, 0, 1, 0]|^2 = 1/6
 * p_6 = |<e_6|psi>|^2 = |(1/sqrt(6)) * [0, 0, 0, 0, 0, 1]|^2 = 1/6

So the probability of obtaining each outcome is 1/6, which is expected since the die is initially in a uniform distribution over all possible outcomes.


To make predictions about the outcomes of measurements using the measurement operator for the 36-dimensional Hilbert space, we need to apply the operator to the quantum state vector representing the initial state of the system, and then calculate the probabilities of obtaining each possible outcome.

Suppose we have an initial quantum state vector represented as:

|psi> = a_1 * e_1 + a_2 * e_2 + ... + a_36 * e_36

where a_i represents the probability amplitude of the system being in the i-th basis state. We can then apply the measurement operator to this state vector as follows:

First, we construct a matrix e whose columns are the basis vectors -> e = ((e_1, e_2, ..., e_36))
Next, we use the outer product to calculate the measurement operator M. This is done by multiplying e with its conjugate transpose -> M = e @ e.conj().T
Finally, to calculate the probabilities of each outcome, we need to take the inner product of the state vector |psi> with the measurement operator M, and then multiply it by its conjugate transpose. This can be expressed as -> p = (M @ |psi>) * (M @ |psi>).conj()
Here, @ denotes matrix multiplication, * denotes element-wise multiplication, and .conj() denotes complex conjugation. 

The probabilities p_i represent the probability of measuring the i-th basis state of the system. Note that the probabilities must satisfy the normalization condition:

sum(p) = |a_1|^2 + |a_2|^2 + ... + |a_36|^2 = 1

which ensures that the total probability of obtaining any outcome is equal to 1.
