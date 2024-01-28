# food-detection-YOLOV8
In this project, a simple food detection YOLOV8 model is developed to detect food. You can access the dataset from [음식 이미지 분류 Image Dataset](https://universe.roboflow.com/calorie-xclip/-970ur/dataset/4).

## Description
Firstly, the dataset is downloaded using the Roboflow API key. then, the pre-trained YOLOV8 model is loaded and fed to the train data. Finally, the MAP metric results are reported for the validation and test sets. Besides, the FPS(frame per second) is computed for the model and the trained model predicts a simple test image(Marinated_seasoning_crab)
In the last part, you could use the OpenAi API key to access the ChatGPT, and feel free to ask anything you wish. I asked GPT to describe the recipe of the food (Marinated_seasoning_crab). (My API key is removed from the client object to preserve my privacy. So, you could use your OpenAi API key to use ChatGPT)

### Test result
![Marinated_seasoning_crab detection](https://github.com/alish1377/food-detection/blob/main/Marinated_seasoning_crab.png)
