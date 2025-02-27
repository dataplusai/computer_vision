# Infra Red Image Object Detection for Night Vision in Roads with low visibility


In this project, we will use infra red image to detect obstacles while traveling in roads with low light visibility. In low light conditions, it will be difficult for drivers to detect obstacles in short time leading to accidents. Using IR images we can avoid these accidents by alerting drivers of any potential obstacles.

We use YOLOv11 pre-trained model from Ultralytics for object detection. When we run inference on a sample image, model detects cars in the image. Attached in this repository is the google Colab notebook for this inference. Sample iamge is taken from :
https://newatlas.com/uncooled-long-wave-infrared-camera/15637/

In future, we would like to convert the python code to tensorflow lite and deploy in a android mobile for real time detection using video from mobile IR camera attached with vehicles. Also model can be fine tuned with IR images of roads with obstacles for increasing object detection accuracy.
