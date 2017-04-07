# Chapter 3: Time Domain Analysis of Continuous Time Systems
-----

## 3.1 Continuous Time Systems
As you already now know, a continuous time system operates on a continuous time signal input and produces a continuous time signal output. There are numerous examples of useful continuous time systems in signal processing as they essentially describe the world around us. The class of continuous time systems that are both linear and time invariant, known as continuous time LTI systems, is of particular interest as the properties of linearity and time invariance together allow the use of some of the most important and powerful tools in signal processing.

## 3.2 Continuous Time Impulse Response 
The output of an LTI system is completely determined by the input and the system's response to a unit impulse. The output for a unit impulse input is called the impulse response.

## 3.3 Continuous Time Convolution
Convolution, one of the most important concepts in electrical engineering, can be used to determine the output a system produces for a given input signal. It can be shown that a linear time invariant system is completely characterized by its impulse response. The sifting property of the continuous time impulse function tells us that the input signal to a system can be represented as an integral of scaled and shifted impulses, and, therefore, as the limit sym of scaled and approximate unit impulses. Thus, by linearity, it would seem reasonable to compute of the output signal as the limit of a sum of scaled and shifted unit impulse responses, and, therefore, as the integral of a scaled and shifted impulse response. That is exactly what the operation of convolution accomplishes. Hence, convolution can be used to determine a linear time invariant system's output from knowledge of the input and the impulse response.

## 3.4 Properties of Continuous Time Convolution
We have already shown the important role that continuous time convolution plays in signal processing. This section provides discussion and proof of some of the important properties of continuous time convolution. Analogous properties can be shown for continuous time circular convolution with trivial modification of the proofs provided except where explicitly noted otherwise.

## 3.5 Eigenfunctions of Continuous Time LTI Systems
Prior to reading this module, the reader should already have some experience with linear algebra and should specifically be familiar with the eigenvectors and eigenvalues of linear operators. A linear time invariant system is a linear operator defined on a function space that commutes with every time shift operator on that function space. Thus, we can also consider the eigenvector functions, or eigenfunctions, of a system. It is particularly easy to calculate the output of a system when an eigenfunction is the input as the output is simply the eigenfunction scaled by the associated eigenvalue. As will be shown, the continuous time complex exponentials serve as eigenfunctions of linear time invariant systems operating on continuous time signals.

## 3.6 BIBO Stability of Continuous Time Systems
BIBO stability stands for bounded input, bounded output stability. BIBO stability is the system property that any bounded input yields a bounded output. This is to say that as long as we input a signal with absolute value less than some constant, we are guaranteed to have an output with absolute value less than some other constant.

## 3.7 Linear Constant Coefficient Differential Equations
In our study of signals and systems, it will often be useful to describe systems using equations involving the rate of change in some quantity. Such equations are called differential equations. For instance, you may remember from a past physics course that an object experiences simple harmonic motion when it has an acceleration that is proportional to the magnitude of its displacement and opposite in direction. Because this equation has only one independent variable and only has derivatives with respect to that variable, it is called an ordinary differential equation. There are more complicated differential equations, such as the Schrodinger equation, which involve derivatives with respect to multiple independent variables. These are called partial differential equations, but they are not within the scope of this module.

## 3.8 Solving Linear Constant Coefficient Differential Equations
The approach of solving linear constant coefficient ordinary differential equations is to find the general form of all possible solutions to the equation and then apply a number of conditions to find the appropriate solution. The two main types of problems are initial value problems, which involve constraints on the solution and its derivatives at a single point, and boundary value problems, which involve constraints on the solution or its derivatives at several points.

The number of initial conditions needed for an Nth order differential equation, which is the order of the highest order derivative, is N, and a unique solution is always guaranteed if these are supplied. Bounday value problems can be slightly more complicated and will not necessarily have a unique solution or even a solution at all for a given set of conditions. Thus, this module will focus exclusively on initial value problems.
