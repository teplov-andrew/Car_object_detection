# Car_object_detection
### About my solution:
I tried to solve the problem of computer vision about the detection of cars. Decided as a training (for myself), so my solution may not be the most optimal and best, but you can use it as a baseline in some competition or a simple CV pipeline.

### Data:
I got data from this [competition](https://ods.ai/competitions/mcs_car_verification).

### Model:
Fine tuning a `fasterrcnn_resnet50_fpn` about 5 epoch and I got not bad resault:
![car_img_1](https://github.com/teplov-andrew/Car_object_detection/blob/main/car_detetcted_image/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202022-07-31%20170344.png)

You can try it yourself with the `show_img_car_detection.ipynb` file.
Мy [weights](https://drive.google.com/file/d/1roFNYHdE9VZb2Mim1R6o0zppuV4R7g9i/view?usp=sharing).

If you want to see the process of creating and training, you can follow the link to my kaggle [notebook](https://www.kaggle.com/code/andrewteplov/pytorch-car-object-detection-fine-tuning)
