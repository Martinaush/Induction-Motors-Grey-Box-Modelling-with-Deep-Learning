# Induction-Motors-Grey-Box-Modelling-with-Deep-Learning
AI Application of Induction motors to forecast future breakdowns.

# Abstract
Deep learning techniques are improving in terms of reliability and effec- tiveness. Particularly, this dissertation studies two approaches in relation with an important and demanded application that focuses on rotating ma- chinery fault diagnosis and classification. Implementing an AI system that can automatically detect faults at an early stage and recommend stopping of a machine to avoid unsafe conditions in the process and environment has become possible.


First Approach: for this scenario the problem consists in simulating precisely the data from an induction motor through Matlab using one of its tools called SimuLink. The resulting successful simulation will work hand in hand with a Deep learning model. SimuLink simulation will be capable of simulating different states of the induction motor, whereas the Deep learning model will be classifying these states appropriately. Moreover, for this approach, we used two induction motor databases: a database provided by UCC containing data of three different induction motors and MAFAULDA database.


Second Approach: this part only uses a well-known machinery fault database called MAFAULDA which is composed of 1951 multivariate time- series acquired by sensors on a SpectraQuest’s Machinery Fault Simulator (MFS) Alignment-Balance-Vibration (ABVT). The 1951 comprises six dif- ferent simulated states: normal function, imbalance fault, horizontal and vertical misalignment faults and, inner and outer bearing faults. Particu- larly, we focused on two accelerometers that measure the vibration of the induction motor (under-hang and overhang) and their three directions: tangential, axial and radial.


The main aim of this approach is to obtain a visualization of the impor- tant parts in the frequency domain of multi-variate time series that trigger the decision in our Deep learning model. With this insight, the possible technician will be able to identify and foresee if the motor is functioning at an unhealthy behavior and stop it if this happened.
In more detail, firstly we apply Fast Fourier Transformation in order to change our input from the time domain to the frequency domain and also, as a dimensionality reduction technique. Secondly, we built, trained and tuned a famous Deep learning technique called 1-D Convolutional Neural Network that classifies different states of the motor. Finally, we use Grad-CAM on the frequency domain of each class in order to highlight the important parts of that trigger the decision of the CNN.
Key words: Fault Detection, Artificial Intelligence, Grad-CAM, CNN, SimuLink, MatLab and Fast Fourier Transformation.
