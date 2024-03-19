<img src="https://raw.githubusercontent.com/RSandAI/HRPlanes/main/Assets/HRPlanes%20Header.png" height=400 width=1280 alt="github.com/RSandAI/HRPlanes"/>

<br>

This repository contains weights for YOLOv4, Faster R-CNN, and YOLOv8 networks trained with the HRPlanes dataset. YOLOv4 training has been performed using Darknet ([link](https://github.com/AlexeyAB/darknet)), while Faster R-CNN has been trained using TensorFlow Object Detection API v1.13 ([link](https://github.com/tensorflow/models/tree/r1.13.0)). YOLOv8 was also built and trained by our team using Ultralytics library ([link](https://github.com/ultralytics/ultralytics)).

## Updates

**The HRPlanes Dataset can be downloaded now! Please see below for details!**

### Latest Update  :rocket:

**February 2024:** The HRPlanes Dataset trained with YOLOv8x is now available for download. Please see below for details.

<br>

# Dataset Details

<img src="https://raw.githubusercontent.com/RSandAI/HRPlanes/main/Assets/HRPlanes%20Samples%20All.png" alt="github.com/TolgaBkm/HRPlanes/"/>

The imagery required for the dataset was obtained from Google Earth. We downloaded 4800 x 2703 sized 3092 RGB images from major airports around the world, such as Paris-Charles de Gaulle, John F. Kennedy, Frankfurt, Istanbul, Madrid, Dallas, Las Vegas, and Amsterdam, as well as aircraft boneyards like Davis-Monthan Air Force Base. The dataset images were manually annotated by creating bounding boxes for each airplane using the HyperLabel software, which still provides annotation services as [Plainsight](https://app.plainsight.ai/). Quality control of each label was conducted through visual inspection by independent analysts who were not involved in the labeling procedure. A total of 18,477 airplanes have been labeled. A sample image and corresponding minimum bounding boxes for airplanes can be seen in the figure below. The dataset has been approximately split as 70% (2170 images) for training, 20% (620 images) for validation, and 10% (311 images) for testing. For those interested in monitoring closely, the sample images used in this dataset can be accessed [here](https://github.com/TolgaBkm/HRPlanes/tree/main/Sample%20Images).

<br>

# Download Model and Weights

| Model   | Description                                                | mAP50  | mAP50-95 | Hyperparameters                                              | Download Weights                                            |
|---------|------------------------------------------------------------|--------|----------|------------------------------------------------------|-----------------------------------------------------|
| YOLOv8x | The model demonstrates robust performance with potential applications in object detection tasks. The training process was completed in 2.503 hours. | 99.3%  | 87.1%    |  - Epochs: 64 <br> - Batch size: 2 <br> - Image size: 640 <br> - Optimizer: auto | [Download](#)                                       |

<br>

 **YOLOv4 Weights and *.cfg* File:** [Download](https://drive.google.com/file/d/1r0AlQE10y21b8bm5pvoj_jtDfDp_-ees/view?usp=sharing)

**Faster R-CNN Frozen Graphs:** [Download](https://drive.google.com/file/d/1L3ho4L7lxxBItVg43zLmnrywQiYrxgWm/view?usp=sharing)

<br>

# Download The Dataset

We are pleased to announce that the entire HRPlanes dataset is now available for download in YOLO format. This dataset, containing annotated images of airplanes from major airports and aircraft boneyards, can be accessed on [Google Drive](https://drive.google.com/drive/folders/1NYji6HWh4HRLQMTagsn4tTv4LOdDrc9P?usp=sharing). Feel free to explore and utilize this rich resource for your research and projects.

If you utilize the HRPlanes dataset in your work, we kindly request that you cite our [paper](https://dergipark.org.tr/tr/pub/ijeg/issue/77206/1107890) to acknowledge our efforts.

<br>

# Download Test Dataset

- **YOLO Format:** [Download](https://drive.google.com/file/d/1UBhs64ximEDmBtbMecg-aMaGMBX4yt8m/view?usp=sharing) - Download the dataset in YOLO format, suitable for use with YOLO models and variants.

- **TFRecord:** [Download](https://drive.google.com/file/d/12MU8_cHpjai46hMsIdPY_X9T-Z6fEbRo/view?usp=sharing) - Download the dataset in TFRecord format, compatible with TensorFlow Object Detection API.


<br>

# Citation

If you make use of the test dataset or weights, please cite our [paper](https://dergipark.org.tr/tr/pub/ijeg/issue/77206/1107890#article_cite) to acknowledge the source.

Bakırman, T. & Sertel, E. (2023). "A benchmark dataset for deep learning-based airplane detection: HRPlanes". International Journal of Engineering and Geosciences, 8(3), 212-223. DOI: 10.26833/ijeg.1107890.

<br>

# Copyright

The use of Google Earth images must respect the ["Google Earth" terms of use](https://about.google/brand-resource-center/products-and-services/geo-guidelines/). All images and their associated annotations can be used for academic purposes only; commercial use is prohibited.

Released under the [Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International (CC BY-NC-ND 4.0) License.](https://creativecommons.org/licenses/by-nc-nd/4.0/)
