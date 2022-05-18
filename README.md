# CNN helicity classifier

Convolutional Neural Network for the classification of helicity of intergalactic magnetic fields. Contains the Jupyter notebook for a basic Convolutional Neural Network my collaborators and I are using to classify helicity of magnetic fields in our intergalatic neighborhood. 

The data consist of simulated photons of energies between 1 GeV and 70 GeV entering our atmosphere. 

## The simulation 

In summary, the simulated process is the following:

A relativistic jet coming out from a blazar, induces electromagnetic cascades by interacting with the extragalactic background. If there is an intergalatic magnetic field, the electrons produced in the cascades propagate in an spiral trayectory, losing energy due to inverse Compton scattering with the Cosmic Microwave Background. The photons from the Compton scattering then travel within a small solid angle and a small portion of them reach the earth where they are observed. 

The spiraling of the electrons due to the magnetic field, induces a relative orientation of the lower energetic photons with respect to the higher energetic ones, as we can see at the simulated picture below (Is hard to see with a human eye, but, for example the green photons, tend to acomodate themselves towards an anti-clockwise direction.)

## The CNN

The data we want to classify, consist of images of simulated photons observed on the sky. He have 600 images of photons which have interacted with an intergalatic magnetic field with plus helicity, and 600 corresponding ones with magnetic fields of helicity minus. The outcome model of the CNN should tell us if a simulation corresponds to a magnetic field of a given helicity, so that hopefully, one can use such trained networks in experiments to identify the real helicity of the magnetic field in the surroundings of our intergalatic neightborhod. 



