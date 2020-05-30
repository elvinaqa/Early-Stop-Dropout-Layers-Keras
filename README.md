# Early-Stop-Dropout-Layers-Keras
One of the ways for handling overfitting is the function of early stop and drop out from training according to the loss condition during the train process.
Dropout layers swithc off some layers and nuerons in certain loss conditions to prevent overfitting.
Each layer drops user-defined number of neurons in previous layer in every batch.


![download](https://user-images.githubusercontent.com/57037068/83325962-8e4b4580-a281-11ea-8216-ac0ebcf2a3c1.png)

# Right in the point when the validation loss increase ( which means overfitting starts, models stops the number of epochs to be trained)


![download (1)](https://user-images.githubusercontent.com/57037068/83325959-88edfb00-a281-11ea-98cc-22065a1f8219.png)


# tracking validation loss  - test set accuracy is low while train is much higher

After 
#dropout

![download (2)](https://user-images.githubusercontent.com/57037068/83326149-9c4d9600-a282-11ea-9af4-8aecbf953020.png)
