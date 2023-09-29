# Neuron Modeling Tutorial
This is a single neuron modeling tutorial developed for the [Imbizo 2023 Summer School](imbizo.africa).

**Title**: Neuron Modeling and Ordinary Differential Equations

**Key Learning Objectives**: 
- The tutorial's aim is to develop a deep intuition for single neuron modeling, and it is in 2 parts*. 
- First is to build a mathematical intuition of first order ordinary differential equations (ODEs), practice analytical and numerical solutions of ODEs, and apply this mathematical knowledge to understand logistic functions as a building block for neuron models. 
- Second is to use knowledge of logistic functions to understand leaky integrate and fire (LIF) neuron models and interrogate the model's input-output relationship by exploring input noise, spike frequency, and spike regularity.
- *Miniprojects encourages students to try implementing nonlinear Integrate and Fire (IF) neuron models and conductance-based neuron models using the material covered in the tutorial

**Basic/Foundational Math concepts**: 
- Calculus - derivation and integration
examples are solved by stepping through the steps of integration as a review for students
- Differential Equations 
ODE tutorial is for students without this math background

**Tutorial Outline**:
- Ordinary Differential Equations Tutorial
  - What is a Differential Equation?
  - Methods of Solution: Analytic and Numerical
  - Constant Growth (Linear Model)
  - Proportional Growth/Decay (Exponential Model)
  - Growth as an asymptote (Logistic Model)
- Leaky-Integrate-and-Fire Tutorial
  - A Return to the Hodgkin Huxley (HH) Equations
  - Building a LIF Model
  - Describing an LIF Model's Input/Output Relationship
    - Visualize LIF Voltage Trace with input noise
    - Generate an Frequency-Current (F-I) Curve
      - How does input noise impact the F-I curve of a LIF Model?
    - Measuring and Visualizing Inter-Spike-Intervals
      - Given a current input, how regularly or irregularly does a neuron spike?
    - Coefficient of Variance
- *Miniprojects
  - More practice with solving ODEs
  - Implementing and Analyzing the Input/Output Relationships of Nonlinear IF Models and IF Models with Adaptation
  - Implementing and Analyzing the Input/Output Relationships of the Hodgkin-Huxley Model


## Access the Tutorials Below
- <a href="https://colab.research.google.com/github/ilennaj/neuron_model_tutorial/blob/master/notebooks/01_ode_tutorial.ipynb" target="_blank"><img alt="Open In Colab" src="https://colab.research.google.com/assets/colab-badge.svg"/></a> **Tutorial 1: ODEs** ([solutions](https://github.com/ilennaj/neuron_model_tutorial/blob/master/notebooks/Solutions_01_ode_tutorial.ipynb))

- <a href="https://colab.research.google.com/github/ilennaj/neuron_model_tutorial/blob/master/notebooks/02_lif_tutorial.ipynb" target="_blank"><img alt="Open In Colab" src="https://colab.research.google.com/assets/colab-badge.svg"/></a> **Tutorial 2: Leaky Integrate and Fire Models** ([solutions](https://github.com/ilennaj/neuron_model_tutorial/blob/master/notebooks/Solutions_02_lif_tutorial.ipynb))


###### If running offline, clone the repositories and find the notebooks in the "notebooks" directory. 

- Tutorial 1: notebooks/Offline_01_ode_tutorial.ipynb
- Tutorial 2: notebooks/Offline_02_lif_tutorial.ipynb
