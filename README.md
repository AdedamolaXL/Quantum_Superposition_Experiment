# Quantum_Superposition_Experiment
A conceptual exploration of superposition behaviour in rolled dice as observed from a video camera


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

Thus the very process of measurement (observation) creates the property which is measured, i.e., it is the very measurement that actualizes the property which, prior to the measurement, was only existing in potential terms {the potential terms here being the 6 faces of the die). 

It's important to recognize that the actualization of potential elements of reality is a characteristic feature of quantum systems, and this leads to non-classical properties that can create interference effects. This suggests that many of the "strange" aspects of quantum physics are actually present in the examination of conventional examples used to demonstrate classical probability calculations since the origin of probability theory. We only need to view these examples as physical experiments assessing particular features or measuring specific observables.

This right here is the source of our thesis, that and a lack of access to quantum precision instrumentation :)


### METHODOLOGY

To prove the existence of quantum superposition, we will need to show that the system exhibits interference effects or other phenomena that are characteristic of superposition. For the purpose of our experiment, ***we will be performing measurements that reveal the coexistence of multiple states with different probabilities.***  
In your die-rolling experiment, we'll associate spin directions with the observed faces and assign probabilities to each spin direction based on the frequencies of occurrence. By performing measurements on the spin direction of the die, we hope to reveal the coexistence of multiple spin directions and their respective probabilities.

*Materials:*
 
 * One die with six sides
 * Flat surface to roll the die on
 * Camera to record the experiment 
 * Notebook to record the results

*Procedure:*

 * Choose a flat surface to roll the die on. Ensure that the surface is level and free from any potential sources of disturbance.
 * Prepare the die by ensuring that it is clean and free from any obstructions that may prevent it from rolling smoothly.
 * Begin the experiment by setting a timer to a fixed duration.
 * At regular intervals, in this case, every 10 seconds, roll the die onto the flat surface. Record the result of each roll on a data sheet.
 * Repeat step 4, to conduct more rolls

*Our experimental scenario:*

For the purpose of this experiment, we are recording the *front face(s)* of the die, which the camera allows us to do due to the 180-degree view. In our experiment, a roll has two possible initial outcomes; one in which a *single-face* is recorded and the other in which *double-faces* are recorded. This scenario will help us to study the phenomenon of quantum superposition where our die is locked in two states. Each face will be analogous to the spin direction, and since our die has 6 faces, we will also have 6 spin directions.

![Screenshot from 2023-06-11 23-25-49](https://github.com/AdedamolaXL/Quantum_Superposition_Experiment/assets/66562380/a7da78f8-dc4a-4347-9900-2122071ca258)
- single face


![Screenshot from 2023-06-11 23-25-36](https://github.com/AdedamolaXL/Quantum_Superposition_Experiment/assets/66562380/0d3e949d-4ed1-4773-a289-b26e83e6a3f5)
- double face

We can write the spin directions for the single-face outcome with their probability amplitude as this:
|1⟩ = α₁
|2⟩ = α₂
|3⟩ = α₃
|4⟩ = α₄
|5⟩ = α₅
|6⟩ = α₆
The probability amplitude can be assigned equally to each direction based on classical probability as: 
α₁ = α₂ = α₃ = α₄ = α₅ = α₆ = 1/6.

For the double-face outcomes, the spin direction for each face can be written as: 
(1,2) = β₁₂
(1,3) = β₁₃
(1,4) = β₁₄
(1,5) = β₁₅
(2,3) = β₂₃
(2,4) = β₂₄
(2,6) = β₂₆
(3,5) = β₃₅
(3,6) = β₃₆
(4,5) = β₄₅
(4,6) = β₄₆
(5,6) = β₅₆

The assigned probabilities will serve as the baseline for the comparison of the measured outcomes for the single-face spin directions and double-face combination spin directions.

### EXPERIMENTAL RESULTS

* total number of rolls: 360
  
* total count of double faces: 207
* number of possible outcomes that can appear on a single face: 6
* count for each side of the single face spin direction observed:

      (1) = 34
      (2) = 40
      (3) = 39
      (4) = 29
      (5) = 29
      (6) = 38

* total count of double faces: 153
* number of possible outcomes that can appear on double faces: 12
* count for the double face spin direction observed:

      (1,2) = 13
      (1,3) = 21
      (1,4) = 15
      (1,5) = 11
      (2,3) = 9
      (2,4) = 12
      (2,6) = 10
      (3,5) = 3
      (3,6) = 15
      (4,5) = 14
      (4,6) = 9
      (5,6) = 21

*Calculating probabilities*
Calculate the observed frequencies for each measurement outcome. Compare these frequencies with the assigned probabilities to assess how well they align wil help us judge the possibilites of the coexistence of multiple states with different probabilities.

We can calculate the probability for single face spin direction in three ways:

Actual probability for a single-face spin direction with the presence of double face combination when the total number of rolls is 360: 
Using the formula P(i) = (Count(i) + Count(i,j) + Count(i,k) + Count(i,l) + Count(i,m)) / Total Rolls
    
    P(1) = 0.225
    P(2) = 0.2333
    P(3) = 0.2417
    P(4) = 0.2194
    P(5) = 0.2167
    P(6) = 0.2583

Actual probability for a single-face spin direction without the presence of double face combination when the total number of rolls is 360:
Using the formula P(i) = Count(i) / Total Rolls

    P(1) = 0.0944
    P(2) = 0.1111
    P(3) = 0.1083
    P(4) = 0.0805
    P(5) = 0.0805
    P(6) = 0.1055

Actual probability for a single-face spin direction counting just single rolls of 207:
Using the formula P(i) = Count(i) / Single-face Rolls

    P(1) = 0.1643
    P(2) = 0.1932
    P(3) = 0.1884
    P(4) = 0.1401
    P(5) = 0.1401
    P(6) = 0.1836

 
Calculating the probabilities of each outcome for a double face using the formula P(i,j) = count(i,j)/total count of double-faces:

      (1,2) = 0.0361
      (1,3) = 0.0583
      (1,4) = 0.0417
      (1,5) = 0.0305
      (2,3) = 0.0250
      (2,4) = 0.0333
      (2,6) = 0.0277
      (3,5) = 0.0083
      (3,6) = 0.0416
      (4,5) = 0.0388
      (4,6) = 0.0250
      (5,6) = 0.0583

## ANALYSIS OF RESULTS

The expected probability for each single face spin direction is 1/6, which is approximately 0.1667. This is the probability we would expect if the die were behaving classically, without any quantum effects.

These probabilities deviate from the expected probabilities of 1/6. The presence of double face combinations seems to affect the probabilities of the single faces, leading to a redistribution of probabilities among the faces.

Comparing these probabilities to the expected probability of 1/6, we can see that they deviate from the classical expectation. This suggests that even in the absence of double face combinations, there are factors influencing the probabilities of the single face spin directions, which may be related to the experimental setup or other unknown factors.

Overall, the deviation from the expected probabilities indicates that the system is exhibiting behavior beyond classical probabilities, possibly influenced by quantum effects such as superposition or entanglement. Further analysis and experimentation would be needed to fully understand and interpret the observed probabilities.

## CONCLUSION
* Coexistence of Multiple States: The experiment has demonstrated the coexistence of multiple states with different probabilities in a macroscopic system. The observed probabilities for single-face spin directions and double-face spin direction combinations indicate that the die can exist in different states simultaneously, each with its own likelihood of occurrence.
* Departure from Classical Behavior: The probabilities obtained from the experiment deviate from the expected classical probabilities. This departure from classical behavior suggests the presence of quantum-like phenomena or non-classical effects in the macroscopic system.

* Influence of Interference: The observed probabilities for both single-face and double-face spin directions suggest the presence of interference effects. The interference between different spin directions, including both single-face and double-face combinations, impacts the overall probability distribution of the system.
