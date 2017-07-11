# General_dnn
	
	the goal of this project is to create a general agent that
	can classify any problem when given a numpy array of the 
	features and labels.

    this class only works with classiftion
    
## dependencys
	
	numpy
	tflearn
	tensorflow

	sklearn 
		for datasets

## format for inputdata
	
	**must be in a 2d array**
	features
		feature data should be in a numpy array of n lenght
		ex:
			[[.12],[.322],[.4322]]
			n = 3

	labels
		feature data should be in a numpy array of n lenght
		ex:
			[[0],[1],[0],[0]]
			n = 4

## tensorboard
	
	to assess tensorboard on unbuntu

	type: tensorboard --logdir /tmp/tflearn_logs/openai_learning/
	into terminal