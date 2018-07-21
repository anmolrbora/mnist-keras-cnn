# mnist-keras-cnn
## Digit Recognition using keras <br>

* Dataset will be automatically downloaded.<br>
* Comment these lines in the notebook: <br>
          ```model = larger_model()``` <br>
          ```model.fit(X_train, y_train, validation_data=(X_test, y_test), epochs=10, batch_size=200, verbose=2)```<br>
          ```scores = model.evaluate(X_test, y_test, verbose=0)```<br>
          ```print("Accuracy: %.2f%%" % (scores[1]*100)) ``` 
* Uncomment ```model=load_model('model.h5')``` if you want to use the saved model. 
* Input the appropriate image directory path after cloning the repository.

Dataset used: <b>MNIST</b><br>

Libraries required: <br>
* [keras](https://keras.io/#installation)<br>
* [TensorFlow](https://www.tensorflow.org/install/)
