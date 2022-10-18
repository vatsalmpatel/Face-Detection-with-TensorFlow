# Face Detection 👽 with TensorFlow

In this project, I worked upon creating a face detection appplication using TensorFlow. This application captures training images using your own webcam, saves them to a folder. Then you annotate those images using ****`labelme`****  library and use image augmentation using `albumentations` to augment those images and create more images for training. After this, I created a model using the `Keras Functional API` to create a model using `VGG16` model architecture. Finally, I used this pre-trained model to detect my face in real-time. 

# How to run the notebook ❓

To run the notebook create a new anaconda environment using:

```Bash
conda create -n new_env_name
```

After creating the new environment, just activate it using

```Bash
conda activate new_env_name
```

After this just install all the dependencies using the `requirements.txt` file:

```Bash
pip install -r requirements.txt
```