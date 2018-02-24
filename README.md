# Cats vs dogs classification using tensorflow
Learning image recognition using sentdexs' tutorial which you can find here: https://pythonprogramming.net/convolutional-neural-network-kats-vs-dogs-machine-learning-tutorial/
<br>
This is my simple attempt to learn about image recognition using tensorflow. After much effort, I did understand what happens in the background.

**Feel free to try out the codes**<br>
Here are the steps: 
1. Make sure you have all the required packages mentioned in `Pipfile`
2. You first need to preprocess your data. Ensure you've downloaded the images from https://www.kaggle.com/c/dogs-vs-cats-redux-kernels-edition/data , Now:
   1. Run `python process_train_data.py` to create the `train_data.npy` file
   2. Then run `python process_test_data.py` to create the `test_data.npy` file
4. Finally, you are ready to create and train your model. Ensure you've uncommented the `create_model` and `train_model` function calls. Do this using `python create_n_train.py`. If you have a slow PC (like I do), this may take a while. 
5. Now you are ready to start the classification. Run `python make_classification.py`

Of course, if you are not an absolute beginner and have some understanding of tensorflow, you can use the `model.meta` file I've provided. 
> Do note: please keep the downloaded images and all the code files from this repository into a single directory. You can ignore this if you plan to tweak the path in the code yourself.

I managed to obtain around 96% accuracy. Some results are here:
<img src="https://github.com/LawrenceVeigas/image-recognition-with-tensorflow/blob/master/classification_results/classification_acc_96.png"><br>
Result2:<br>
<img src="https://github.com/LawrenceVeigas/image-recognition-with-tensorflow/blob/master/classification_results/classification_2_acc_96.png">

Not the best, but good enough for a beginner!
