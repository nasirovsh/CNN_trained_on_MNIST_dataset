# CNN_trained_on_MNIST_dataset
Trains a simple convnet on the MNIST dataset.  Gets to 99.25% test accuracy after 12 epochs (there is still a lot of margin for parameter tuning). 16 seconds per epoch on a GRID K520 GPU.


Sample output:

Train on 60000 samples, validate on 10000 samples  

Epoch 1/12  
60000/60000 [==============================] - 134s 2ms/step - loss: 0.2621 - acc: 0.9200 - val_loss: 0.0541 - val_acc: 0.9818   
Epoch 2/12  
60000/60000 [==============================] - 140s 2ms/step - loss: 0.0875 - acc: 0.9743 - val_loss: 0.0420 - val_acc: 0.9869  
Epoch 3/12  
60000/60000 [==============================] - 150s 2ms/step - loss: 0.0664 - acc: 0.9804 - val_loss: 0.0358 - val_acc: 0.9884  
Epoch 4/12  
60000/60000 [==============================] - 154s 3ms/step - loss: 0.0537 - acc: 0.9833 - val_loss: 0.0336 - val_acc: 0.9890  
Epoch 5/12  
60000/60000 [==============================] - 147s 2ms/step - loss: 0.0481 - acc: 0.9850 - val_loss: 0.0300 - val_acc: 0.9900  
Epoch 6/12  
60000/60000 [==============================] - 139s 2ms/step - loss: 0.0411 - acc: 0.9869 - val_loss: 0.0283 - val_acc: 0.9905  
Epoch 7/12  
60000/60000 [==============================] - 139s 2ms/step - loss: 0.0380 - acc: 0.9885 - val_loss: 0.0287 - val_acc: 0.9910  
Epoch 8/12  
60000/60000 [==============================] - 132s 2ms/step - loss: 0.0342 - acc: 0.9894 - val_loss: 0.0261 - val_acc: 0.9913  
Epoch 9/12  
60000/60000 [==============================] - 128s 2ms/step - loss: 0.0318 - acc: 0.9906 - val_loss: 0.0277 - val_acc: 0.9917  
Epoch 10/12  
60000/60000 [==============================] - 154s 3ms/step - loss: 0.0291 - acc: 0.9910 - val_loss: 0.0296 - val_acc: 0.9909  
Epoch 11/12  
60000/60000 [==============================] - 162s 3ms/step - loss: 0.0289 - acc: 0.9913 - val_loss: 0.0281 - val_acc: 0.9922  
Epoch 12/12  
60000/60000 [==============================] - 138s 2ms/step - loss: 0.0266 - acc: 0.9916 - val_loss: 0.0257 - val_acc: 0.9918  

Test loss: 0.02574768212585259  
Test accuracy: 0.9918  
