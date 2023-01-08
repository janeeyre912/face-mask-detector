# Project Title:
## _face-mask-detector_
Develop an AI that can analyze face images and detect whether a person is wearing a face mask or not, as well as the type of mask that is being worn: no face mask, cloth mask, surgical mask or N95 mask.
## Datasets:
img folder --sample(100 images for evaluation)<br />
           |     --cloth    (25 images) <br />
           |     --n95      (25 images)<br />
           |     --nomask   (25 images)<br />
           |     --surgical (25 images)<br />
            --train(1600 images for train)<br />
           |     --cloth    (400 images) <br />
           |     --n95      (400 images)<br />
           |     --nomask   (400 images)<br />
           |     --surgical (400 images)<br />
## Source code:
a)training <br />
masks_detector_train.py <br />
Running this code to transform the images of the dataset in uniform, use the built CNN to train
the model, and will generate the evaluation results used by the random split test set. And it will
save the trained model in model.pkl.<br />
b)application<br />
masks_detector.py<br />
Running this code to load the saved trained model to evaluate with the sample data(100 images).<br />
## Trained model:
model.pkl <br />
## Project report:



