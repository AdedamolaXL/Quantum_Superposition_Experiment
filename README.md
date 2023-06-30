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

Thus the very process of measurement (observation) creates the property which is measured, i.e., it is the very measurement that actualizes the property which, prior to the measurement, was only existing in potential terms {the potential terms here being the 6 faces of the die). 

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

![Screenshot from 2023-06-11 23-25-49](https://github.com/AdedamolaXL/Quantum_Superposition_Experiment/assets/66562380/a7da78f8-dc4a-4347-9900-2122071ca258)

![Screenshot from 2023-06-11 23-25-36](https://github.com/AdedamolaXL/Quantum_Superposition_Experiment/assets/66562380/0d3e949d-4ed1-4773-a289-b26e83e6a3f5)




### RESULTS AND DISCUSSION

* total count of single faces: 207

* number of possible outcomes that can appear on a single face: 6
* count for each side of the single face observed:

      (1) = 34
      (2) = 40
      (3) = 39
      (4) = 29
      (5) = 29
      (6) = 38

Calculating the probabilities of each outcome for a single face using the formula P(i) = count(i)/total count of single faces:

    P(1) = 34/360 ≈ 0.0944
    P(2) = 40/360 ≈ 0.1111
    P(3) = 39/360 ≈ 0.1083
    P(4) = 29/360 ≈ 0.0805
    P(5) = 29/360 ≈ 0.0805
    P(6) = 38/360 ≈ 0.1055
    
We can use this P(x) value to construct the diagonal matrix D:

    [ 0.1643   0        0        0        0        0     ]
    [ 0        0.1932   0        0        0        0     ]
    [ 0        0        0.1884   0        0        0     ]
    [ 0        0        0        0.1401   0        0     ]
    [ 0        0        0        0        0.1401   0     ]
    [ 0        0        0        0        0        0.1836]


* total count of double faces: 153
* number of possible outcomes that can appear on double faces: 12
* count for the possible combination that appeared:
    
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
    
We can use this P(x) value to construct the diagonal matrix M:

    [ 0        0.08497  0.13725  0.09804  0.07190  0        0.06536  0        0.09804  0.05882  0        0.13725 ]
    [ 0.08497  0        0.05882  0.07843  0        0.06536  0        0        0        0.09150  0.13725  0       ]
    [ 0.13725  0.05882  0        0        0.01961  0        0        0.09804  0.09804  0        0.13725  0       ]
    [ 0.09804  0.07843  0        0        0        0.09150  0        0.05882  0.05882  0        0        0       ]
    [ 0.07190  0        0.01961  0        0        0        0.07843  0.09804  0        0.09150  0        0.13725 ]
    [ 0        0.06536  0        0.09150  0        0        0.09804  0.05882  0.05882  0.13725  0        0       ]
    [ 0.06536  0        0        0        0.07843  0.09804  0        0.13725  0        0        0.01961  0       ]
    | 0        0        0.09804  0.05882  0.09804  0.05882  0.13725  0        0        0        0        0       ]
    [ 0.09804  0        0.09804  0.05882  0        0.05882  0        0        0        0.01961  0.13725  0       ]
    [ 0.05882  0.09150  0        0        0.09150  0.13725  0        0        0.01961  0        0        0       ]
    [ 0        0.13725  0.13725  0        0        0        0.01961  0        0.13725  0        0        0       ]
    [ 0.13725  0        0        0        0.13725  0        0        0        0        0        0        0       ]


Next, we need to demonstrate that the measurement operator for the double face outcome is a linear combination of the measurement operator for the single face outcome.

The Kronecker product of a matrix D with a matrix M is denoted by D ⊗ M, and is defined as follows:

* (D ⊗ M)ij = Dij * M ......(vi)

The result of the kron product for the quantum superposition of single and double faces from earlier:
        
    [0          0.01396057 0.02255018     0          0          0         ]
    [0.01396057 0          0.00966413     0          0          0         ]
    [0.02255018 0.00966413 0              0          0          0         ]
    [0          0          0              0          0          0         ]
    [0          0          0              0          0          0         ]
    [0          0          0              0          0          0         ]

The resulting matrix represents the combined state of the quantum system, which is a superposition of the single and double face outcomes. Each element in the matrix corresponds to the probability amplitude of a particular basis state. 

To obtain the actual probabilities, you need to take the absolute value squared of each amplitude:

    [0          0.00019489 0.00050851     0          0          0         ]
    [0.00019489 0          0.00966413     0          0          0         ]
    [0.00050851 0.00009339 0              0          0          0         ]
    [0          0          0              0          0          0         ]
    [0          0          0              0          0          0         ]
    [0          0          0              0          0          0         ]
