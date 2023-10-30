# Trump-card-poker-game-recognition
Detect 
* Repository for archiving team project in March 2021 ~ June 2021
* Junghwan Lee, Kwangsoo Seol

## Introduction
Detect Trump cards and scoring according to the poker game rule on Jetson Nano in real-time.
We used yolov4 tiny model to detect and classify trump cards.
We trained [darknet](https://github.com/AlexeyAB/darknet) model using [Trump card dataset](https://github.com/okmd/playing-card-dataset)
We converted darknet model into ONNX model and optimized it using TensorRT.

## Results

* Result 1
![example_1](https://github.com/kukwang/Trump-card-poker-game-recognition/assets/52880303/b53eb294-4a69-4ec1-aec7-ec0d55061fee)

* Result 2
![example_2](https://github.com/kukwang/Trump-card-poker-game-recognition/assets/52880303/176feea1-1815-41d7-876a-48ef12b723b9)

* Result 3
![example_3](https://github.com/kukwang/Trump-card-poker-game-recognition/assets/52880303/adc449cc-421c-4102-bc0c-fc022c0749e0)


## Acknowledgements
Our code is based on [TensorRT Demo](https://github.com/jkjung-avt/tensorrt_demos)
