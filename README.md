# Simple Pokemon Image Classifier using CNN



## Getting Started

Our deep learning dataset consists of 1,191 images of Pokemon, (animal-like creatures that exist in the world of Pokemon, the popular TV show, video game, and trading card series).

Our goal is to train a Convolutional Neural Network using Keras and deep learning to recognize and classify each of these Pokemon.

The Pokemon we will be recognizing include:

    Bulbasaur (234 images)
    Charmander (238 images)
    Squirtle (223 images)
    Pikachu (234 images)
    Mewtwo (239 images)


### Prerequisites

	1.  Python 2.7 or above
	2.  Scipy
	3.  SKlearn
	4.  Matplotlib
	5.  Numpy
	6.  Keras

## Running the tests


Training :

	python train.py --dataset dataset --model pokedex.model --labelbin lb.pickle

Classifying :

	python classify.py --model pokedex.model --labelbin lb.pickle --image examples/charmander_counter.png



## Authors


	Ishna K A
	
	Anoop Kumar V

	Rahul Kumar M S 




