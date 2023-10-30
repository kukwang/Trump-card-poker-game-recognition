# Trump-card-poker-game-recognition
* Repository for archiving team project in March 2021 ~ June 2021
* Junghwan Lee, Kwangsoo Seol

## Introduction
Detect Trump cards and scoring according to the poker game rule on Jetson Nano in real-time.
We used yolov4 tiny model to detect and classify trump cards.
We trained [darknet](https://github.com/AlexeyAB/darknet) model using [Trump card dataset](https://github.com/okmd/playing-card-dataset)
We converted darknet model into ONNX model and optimized it using TensorRT.

## Results

* Result 1
![example_1](https://github.com/kukwang/Trump-card-poker-game-recognition/assets/52880303/67c5f2fe-1068-4e89-b1a6-08ac9df7252d)

* Result 2
![example_2](https://github.com/kukwang/Trump-card-poker-game-recognition/assets/52880303/e6615de0-35ce-4618-86f4-1fb05da9f69a)

* Result 3
![example_3](https://github.com/kukwang/Trump-card-poker-game-recognition/assets/52880303/a720ebf7-554e-4d9e-8dea-e557e3a4f464)

## Acknowledgements
We referenced the source code in [TensorRT Demo](https://github.com/jkjung-avt/tensorrt_demos)
