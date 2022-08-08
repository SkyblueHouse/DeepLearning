# Practice for predicting survival rate of patients (Surgery for Lung Cancer)

colab : https://github.com/hyunhwalee/DeepLearning/blob/main/colab/run_project/colab_01_My_First_Deeplearning.ipynb

by Gilbut

1. Data
2. Tensorflow (Sequential, Dense)
3. Library 

### The Sequential Model
When to use a Sequential model
A Sequential model is appropriate for a plain stack of layers where each layer has exactly one input tensor and one output tensor.
- https://keras.io/guides/sequential_model/

### Dense Layer


#### Core Layer
- Input object
- Dense layer
- Activation layer
- Embedding layer
- Masking layer
- Lambda layer


`model = Sequential()
model.add(Dense(30, input_dim=17, activation='rule'))
model.add(Dense(1, activation='sigmoid'))
model.compile(loss='binary_crossentropy', optimizer='adam', metrics=['accuracy'])
model.fit(X,Y, epochs=100, batch_size=10)`

