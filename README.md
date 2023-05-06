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

For the case where the camera captures only one face of the die, we can define a 6-dimensional complex vector space where each dimension corresponds to one of the possible outcomes, i.e., the faces of the die numbered 1 to 6. Let's denote the basis vectors for this space as |1⟩, |2⟩, |3⟩, |4⟩, |5⟩, and |6⟩, respectively. Then any state in this space can be represented as a linear combination of these basis vectors, such as:

|ψ⟩ = a1|1⟩ + a2|2⟩ + a3|3⟩ + a4|4⟩ + a5|5⟩ + a6|6⟩,

where a1, a2, a3, a4, a5, and a6 are complex coefficients.

For the case where the camera captures two faces of the die, we can define a 36-dimensional complex vector space where each dimension corresponds to a pair of faces of the die. We can order the pairs lexicographically so that the basis vectors are ordered as:

|1,1⟩, |1,2⟩, |1,3⟩, |1,4⟩, |1,5⟩, |1,6⟩, |2,1⟩, |2,2⟩, ..., |6,5⟩, |6,6⟩.

Then any state in this space can be represented as a linear combination of these basis vectors, such as:

|ψ⟩ = a11|1,1⟩ + a12|1,2⟩ + ... + a66|6,6⟩,

where a11, a12, ..., a66 are complex coefficients.

This construction satisfies the conditions for a Hilbert space, as it is a complex vector space with an inner product that satisfies the properties of linearity, conjugate symmetry, and positive definiteness.

M1 = [1 0 0 0 0 0
      0 0 0 0 0 0  
      0 0 0 0 0 0
      0 0 0 0 0 0     
      0 0 0 0 0 0     
      0 0 0 0 0 0]]


