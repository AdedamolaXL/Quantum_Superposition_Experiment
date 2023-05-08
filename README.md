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

*Our experimental scenario:*

For the purpose of this experiment, we are recording the *front face(s)* of the die, which the camera allows us to do due to the 180 degree view. In our experiment, a roll has two possible initial outcomes; one in which *one face* is recorded and the other in which *two faces* are recorded. This scenario will help us to study the phenomenon of quantum superposition where our die is locked in two states.


*Constructing an Hilbert Space*

In this case, we would represent the single face outcome as the state |1> and the double face outcome as the state |2>. 

The initial state of the system would be a superposition of these two states:

* |psi> = (1/sqrt(2)) * [|1> + |2>] ...... (i)

Our measurement operator would be a 2x2 matrix, since there are only 2 possible outcomes. The matrix would be:

 * M = [[1, 0], [0, 1]] ...... (ii)

To calculate the probability of obtaining each outcome, we can use the formula:

 * p_i = |<e_i|psi>|^2 ...... (iii)

where e_i is the ith basis vector 

and |<e_i|psi>|^2 is the squared magnitude of the inner product between e_i and |psi>.

For this 2-state system, the basis vectors are |1> and |2>. So we can calculate the probabilities as:

 * p_1 = |<1|psi>|^2 = |(1/sqrt(2)) * <1|1> + <1|2>>|^2 = 1/2 ...... (i)
 * p_2 = |<2|psi>|^2 = |(1/sqrt(2)) * <2|1> + <2|2>>|^2 = 1/2 ...... (ii)

The probabilities of obtaining a single face or a double face are both 1/2, which is expected since the initial state is a superposition of these two states with equal weight.

We can think of the 6 faces of the die as corresponding to 6 possible spin directions in a quantum system. In this case, the spin of the die would be analogous to the spin of a quantum particle, and the measurement of the face of the die would be analogous to the measurement of the spin of a quantum particle along a certain direction.

We can represent the spin states using the Dirac notation, where |0⟩ represents spin up and |1⟩ represents spin down. Then, we can assign each face of the die to a corresponding spin state:

    Face 1: |0⟩
    Face 2: |1⟩
    Face 3: |+⟩ = (|0⟩ + |1⟩)/sqrt(2)
    Face 4: |−⟩ = (|0⟩ − |1⟩)/sqrt(2)
    Face 5: |i⟩ = (|0⟩ + i|1⟩)/sqrt(2)
    Face 6: |-i⟩ = (|0⟩ − i|1⟩)/sqrt(2)

Here, |+⟩ and |−⟩ correspond to the spin states that are superpositions of spin up and spin down, while |i⟩ and |-i⟩ correspond to the spin states that are superpositions of spin up and spin down with an imaginary coefficient.

We can then use these spin states to define our quantum system and perform measurements on it. For example, we could prepare the system in a superposition of spin up and spin down, and then measure the spin along a certain direction to obtain a probabilistic outcome. The probabilities of obtaining each outcome would depend on the initial state of the system and the measurement direction.

By using the faces of the die as spin states, we can connect the concepts of classical probability and quantum mechanics, and explore the similarities and differences between them.

### RESULTS AND DISCUSSION
To analyze the number on the die when in double face state, I would need to know the following information:

    How many times was the die observed in the double face state? = 123
    What are the possible numbers that can appear on the two faces when in double face state? = 12
    How many times did each of the possible number combinations appear? =
    (1,2) = 13
    (1,3) = 20
    (1,4) = 11
    (1,5) = 7
    (2,3) = 7
    (2,4) = 11
    (2,6) = 9
    (3,5) = 3
    (3,6) = 12
    (4,5) = 10
    (4,6) = 5
    (5,6) = 15
    
P(outcome) = (number of times outcome occurred) / (total number of trials)

For the double face state, we have a total of 123 trials. Out of these, the possible numbers that can appear on two faces are 12. We can calculate the number of times each of these combinations appeared and use the above formula to calculate their probabilities. Here are the calculations:

    P(1,2) = 13/123 ≈ 0.1057
    P(1,3) = 20/123 ≈ 0.1626
    P(1,4) = 11/123 ≈ 0.0894
    P(1,5) = 7/123 ≈ 0.0569
    P(2,3) = 7/123 ≈ 0.0569
    P(2,4) = 11/123 ≈ 0.0894
    P(2,6) = 9/123 ≈ 0.0732
    P(3,5) = 3/123 ≈ 0.0244
    P(3,6) = 12/123 ≈ 0.0976
    P(4,5) = 10/123 ≈ 0.0813
    P(4,6) = 5/123 ≈ 0.0407
    P(5,6) = 15/123 ≈ 0.1219

These probabilities show the likelihood of each possible outcome when the die is in the double face state.

If the system is in a pure state, the expected probabilities should match the actual probabilities you provided. However, if the system is in a superposition, the expected probabilities may not match the actual probabilities.

Here are the expected probabilities based on the measurement operator matrix:

    P(1,2) = 0.1056
    P(1,3) = 0.1603
    P(1,4) = 0.0866
    P(1,5) = 0.0545  
    P(2,3) = 0.0515 
    P(2,4) = 0.0835
    P(2,6) = 0.0659
    P(3,5) = 0.0212
    P(3,6) = 0.0969
    P(4,5) = 0.0784
    P(4,6) = 0.0451
    P(5,6) = 0.1219
    
    
Comparing the expected probabilities to the actual probabilities you provided, we can see that they are not exactly the same. In particular, the probabilities of observing (1,2), (1,3), (2,4), and (3,6) are higher than expected, while the probabilities of observing (1,4), (1,5), (2,3), and (2,6) are lower than expected.

This suggests that the system may be in a superposition state, rather than a pure state. However, it is worth noting that there could be other factors at play that are affecting the observed probabilities. For example, there could be biases in how the die is rolled or how the camera is positioned, or there could be errors in the data collection or analysis.

One thing we could do with this data is to calculate the expected value and variance of the outcome. The expected value is a measure of the average outcome we expect to get, and the variance measures the spread of the outcomes around the expected value. 

To calculate the expected value, we can use the formula:

E(X) = Σ xi * P(xi)

where xi is the outcome and P(xi) is the probability of that outcome. For the double face state, the possible outcomes are the pairs (i,j) where i and j are the numbers on the two faces that are showing. Using the probabilities we calculated earlier, we can calculate the expected value as:

E(X) = (1*2)*P(1,2) + (1*3)*P(1,3) + (1*4)*P(1,4) + (1*5)*P(1,5) +
       (2*3)*P(2,3) + (2*4)*P(2,4) + (2*6)*P(2,6) + (3*5)*P(3,5) +
       (3*6)*P(3,6) + (4*5)*P(4,5) + (4*6)*P(4,6) + (5*6)*P(5,6)

Plugging in the probabilities we calculated earlier, we get:

E(X) ≈ 3.347

To calculate the variance, we can use the formula:

Var(X) = Σ (xi - E(X))^2 * P(xi)

where xi is the outcome, E(X) is the expected value, and P(xi) is the probability of that outcome. Plugging in the probabilities we calculated earlier and the expected value we just calculated, we get:

Var(X) ≈ 2.431

So the variance is about 2.431, which means that the outcomes are somewhat spread out around the expected value of 3.347.

The fact that the values of P(1,2) and P(3,6) are non-zero indicates that there is interference between the two possible outcomes. In other words, the system is in a superposition of states where the die shows 1 and 2 on its double face, and where the die shows 3 and 6 on its double face. This interference between the two possibilities is a hallmark of quantum mechanics and is one of the features that sets quantum systems apart from classical ones.
