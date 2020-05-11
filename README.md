# # [Global-Wheat-Detection](https://www.kaggle.com/c/global-wheat-detection)

The challenge in this Kaggle competition is to detect the wheat heads and draw bounding boxes around all the detected wheat heads in the given image. Here are a few example of the predictions generated using FasterRCNN model:


<p float="left">
  <img src="./images/preds1.png" width="250" />
  <img src="./images/preds2.png" width="250" /> 
  <img src="./images/preds3.png" width="250" />
</p>

Here are a few approaches I tried to approach the problem with brief description and achieved score on public leader board.

## Experiment #1 (0.6426 on public LB)
- Used model: Pre-trained FasterRCNN
- No image augmentations
- Other settings:
  - Image size:1024 x 1024
  - No CV
  - 5 Epochs
  - Batch size: 16 images
 
