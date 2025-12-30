# Shoes-Classification
## Short description 

Have you have trouble in determine the kinds of your shoes? or the shoes, which is in the shop, isn't the kind that the saler said? This Shoes Classification program can help you.

## The Algorithm

The Shoes Classification is based on jetson-inference and nano,  there are 670 pictures in the dataset of Shoes Classification in total. I use python to let machine to training the model that can divided the photos in five kinds of shoes. When we put a picture in it, we will get a piture with the similarity. Like 80 percent for Clog. The machine determine the kinds of shoes according to the large data in the dataset. It can find the most similarity result. 


## Running this project

1: First, make sure the project is in ~/jetson-inference/python/training/classification$
2: Second, write : imagenet.py --model=$NET/resnet18.onnx --input_blob=input_0 --output_blob=output_0 --labels=$DATASET/labels.txt $DATASET/test/Boat(THis is where your picture in)/12345.jpeg(This is the picture's name) boat0123.jpeg(This is what your new pitrue's name)
3: And then, wait for the result

2. Make sure to include any required libraries that need to be installed for your project to run.
   

[View a video explanation here](https://youtu.be/3a3tM9i6gS0)
