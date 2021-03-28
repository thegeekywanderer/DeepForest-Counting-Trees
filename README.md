# DeepForest-Counting-Trees-Demo
This is an example of using DeepForest to count number of trees in the given image
## Implemented on the pretrained NEON model of DeepForest
An example of one of the prediction window on an low resolution image made by the model is: 
![Prediction Example](/prediction_boxes/predicted17.jpg)
### It should be noted that this is just the capabililty of the pretrained model and can be further trained to produce even better results

## Installation
```
conda create env -n deepforest python=3.6 pip
conda activate deepforest
pip install -r requirements.txt
```
Run the notebook
```
jupyter-notebook
```
