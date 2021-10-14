# CNN_helicity_classifier

Convolutional Neural Network for the classification of helicity of intergalactic magnetic fields. Contains the Jupyter notebook for a basic Convolutional Neural Network my collaborators and I are using to classify helicity of magnetic fields in our intergalatic neighborhood. 

The data consist of simulated photons of energies between 1 GeV and 70 GeV entering our atmosphere. 

## The simulation 

In summary, the simulated process is the following:

A relativistic jet coming out from a blazar, induces electromagnetic cascades by interacting with the extragalactic background. If there is an intergalatic magnetic field, the electrons produced in the cascades propagate in an spiral trayectory, losing energy due to inverse Compton scattering with the Cosmic Microwave Background. The photons from the Compton scattering then travel within a small solid angle and a small portion of them reach the earth where they are observed. 

The spiraling of the electrons due to the magnetic field, induces a relative orientation of the lower energetic photons with respect to the higher energetic ones, as we can see at the simulated picture below (Is hard to see with a human eye, but, for example the green photons, tend to acomodate themselves towards an anti-clockwise direction.)


<img width="1080" alt="Screen Shot 2021-07-14 at 2 56 43 PM" src="https://user-images.githubusercontent.com/74635036/137376314-91b3079c-35bf-49f0-9f35-f00e437e1d86.png">

The image above represents a simulation of what an experiment capturing gamma-ray photons will see. The code for the simulation has been created by Francis Duplesis. Here we are only concern with using the outcome data to train a CNN.

## The CNN

The data we want to classify, consist of images of simulated photons observed on the sky. He have 600 images of photons which have interacted with an intergalatic magnetic field with plus helicity, and 600 corresponding ones with magnetic fields of helicity minus. The outcome model of the CNN should tell us if a simulation corresponds to a magnetic field of a given helicity, so that hopefully, one can use such trained networks in experiments to identify the real helicity of the magnetic field in the surroundings of our intergalatic neightborhod. 



