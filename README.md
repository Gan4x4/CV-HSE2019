# CV-HSE2019
Pytorch examples for "Computer Vision Technology"
https://www.hse.ru/ba/se/courses/292660280.html

## HW

[Basic image operations (Pytorch HW)](/helloworld/HelloWorld.ipynb)

- Load image and classes names
- Convert image to tensor
- Run pretrained classifier
- Convert image from OpenCV format to PIL and Pytorch tensor

[Dataset and Dataloader](helloworld/Dataset_and_Dataloader.ipynb)
- Create dataset from set of images
- Make augmentation by Pytorch transforms
- Add user defined transforms

[Change existing model](helloworld/Change_model_structure.ipynb)
- Add or modify layers of exsting PyTorch model 

## Train

[Gradients flow](train/Understanding_grads.ipynb)
- Gradient storing and weights updating in PyTorch

[Training model on custom dataset](train/Train_with_Tensorboard.ipynb)
- Finetune model on custom dataset, freeze layers 
- Save weights on Google drive
- Access Tensorboard from colab in convenient way

## Video

[Template for object detection (excercise)](video/exercise.ipynb)
- example of using Yolov3 detector

[Action recognition](video/Action_recognition.ipynb)
- Recognize action with 3D model (Resnet3D)
- Auto annotate video 

[Increase model performance](video/Performance.ipynb)
- Move frame format conversion to GPU
- Half precision
- Change receptive field of model
- Increase batch size
- Use IterableDataset

## Extra

[Obtain Masks form YOLACT](extra/YOLACT_get_mask.ipynb)

[Detection colors of an image](extra/Base_colors_detection.ipynb)
- Image color quantization with pillow package
- Get name of primary colors

[Detection human eye blinks](extra/Eye_blink_detection.ipynb)
- Getting facial landmarks
- Blink detector
