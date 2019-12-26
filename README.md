# TAU Vehicle Type Recognition Competition
This is my work on the [TAU Vehicle Type Recognition Competition](https://www.kaggle.com/c/vehicle/overview) Kaggle competition. In this repository you can find the Jupyter Notebook in which I want to show some concepts and techniques that are useful not only in image classification competitions, but also in other computer vision problems.

## Downloading the dataset
First, we need to download the dataset and organize it in such way that will be comfortable to work with. Because images in the dataset have different resolutions, I resized them to 512x512 pixels. The prepared dataset can be downloaded from Kaggle ([Kaggle link](https://www.kaggle.com/markseliaev/tut-images-512/)).

## Installing required packages
Run `pip install -r requirements.txt`. To work with images I used `torchvision`, `opencv` and `Pillow`. To train neural networks I used [PyTorch](https://github.com/pytorch/pytorch). To augment images I used `torchvision` along with [albumentations](https://github.com/albumentations-team/albumentations).

## Cloud environment
I trained my models on Google Colab, so in the notebook there are some colab-specific procedures that are always different in other environments.

## Results
I was able to achieve 0.87 accuracy both on public leaderboard and private leaderboard. You can check out [competition discussions page](https://www.kaggle.com/c/vehicle/discussion) to get other useful ideas on how to impove model accuracy.