# Practice for predicting survival rate of patients (Surgery for Lung Cancer)

colab : https://github.com/hyunhwalee/DeepLearning/blob/main/colab/run_project/colab_01_My_First_Deeplearning.ipynb

by Gilbut

1. Data
2. Keras / Tensorflow (Sequential, Dense) * ex: Your DL project is your journey - Keras : Controller / Tensorflow : Airplane 
3. Library 

### The Sequential Model
When to use a Sequential model
A Sequential model is appropriate for a plain stack of layers where each layer has exactly one input tensor and one output tensor.
(https://keras.io/guides/sequential_model/)

- Tensor : Tensors are multi-dimensional arrays with a uniform type / All tensors are immutable like Python numbers and strings: you can never update the contents of a tensor, only create a new one. (https://www.tensorflow.org/guide/tensor)

### Dense Layer


#### Core Layer
- Input object
- Dense layer
- Activation layer
- Embedding layer
- Masking layer
- Lambda layer


### Build Model and Run it!

`model = Sequential()`<br>
`model.add(Dense(30, input_dim=17, activation='rule'))`<br>
`model.add(Dense(1, activation='sigmoid'))`<br>
`model.compile(loss='binary_crossentropy', optimizer='adam', metrics=['accuracy'])`<br>
`model.fit(X,Y, epochs=100, batch_size=10)`

