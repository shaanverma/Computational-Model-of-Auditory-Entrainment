### Welcome to my project!

This site showcases my implementation and manipulation of the theoretical entrainment model presented in the paper ["A Computational Model of Auditory Entrainment"](https://www2.securecms.com/CCNeuro/docs-0/592888da68ed3f664d8a2567.pdf) by Saleh and Tomasso. First, the neccessary background information is presented in order to understand both the theory and implementation of the model presented. Next, the project objectives, methods, code, and results are showcased.

### Auditory Entrainment
* **Entrainment**: Synchronization of an oscillatory system(s) to an external rhythm/system
   * More efficient processing of stimuli
* Entrainment of auditory neurons depends on properties of input stimuli: amplitude (volume), frequency, and rhythm
* Entrainment is more likely to occur...
   * As stimulus frequency approaches intrinsic frequency and as stimulation intensity increases
* Plays an important role in auditory selective attention


![EntrainmentFigure](entrainment.png)


### Project Objective
* Implement the computational model of auditory neurons presented in the paper, A Computational Model of Auditory Entrainment.
* Explore the behaviour of our model when the intrinsic neuronal properties change.
* Give the neuron a pure tone input (sinusoidal current) instead of a step current.

### Methods
Primary auditory neurons were modeled as phase-locked leaky integrate-and-fire (PL-LIF) cells by modifying the standard LIF equation as follows:

![A cute kitten](LIF.png)

where r is resistance and i(t) is input current, a is the oscillation amplitude, f is the
oscillation frequency, and b is the phase.

The authors determined the oscillation frequency and phase by two entrainment
functions: greedy entrainment and attended entrainment, we didn’t use either.

## Results




