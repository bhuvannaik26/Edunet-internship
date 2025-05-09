WEEK - 1 Basic understanding of DeepLearning concepts like CNN's and ANN's.
WEEK - 2 Start of the project
  -- getting the path to kaggle dataset using kaggle API.
  -- importing libraries like numpy for handling linear mathematics,matplotlib for data visualization and tensorflow for model setup.
  -- making sure to change the runtime to GPU
  -- getting the directories of test,train and validation datasets
  -- letting to know the number of classes and print them and visualize each class like 'fire' and no 'fire'.
  -- In preprocessing, setting the batch size to 32,height and weight to 150 and generate the data over height,width and channels
  -- map the indices and build the model using 3-Convo2D,maxpooling,flatten to reduce from n-D to lower D spaces,Dense with a value of 512 neurons to fire.
  -- Dropout of 0.5 to prevent overfitting
  -- Optimize the model using 'adam' and loss function binary_crossentropy and activation function RELU to adjust the weights
  --summarize the model and print it
        Calculating parameters for each layerusing formulae:
            -- param = (kernel_ht*kernel_wt*channel + 1)* N0.of filters.
            -- denselayer = (Input + 1)*No.of Neurons.
    
