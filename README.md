# Face-Expression-Recognition
A deep learning model for real time prediction of face expressions. 


## Usage
This project can be used to detect expressions and put bounding boxes on a video containing a person's face. This video can be pre-recorded or from the webcam of your pc

## How to run
This project contains the required files (model.json and model_weights.json) which contains the weights and architectures of the pre-trained model executed in the jupyter notebook.

After changing the required paths to appropriate values and installing the required python libraries, the script can be run using a single python command

```
python3 main.py
```
Setup your pc with tensorflow GPU to get fast results (otherwise the program takes foreve to run as well as the flask app is not able to show predictions)
