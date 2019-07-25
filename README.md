# Attention Guided Network for Retinal Image Segmentation (AG_Net)
The code of "Attention Guided Network for Retinal Image Segmentation" in MICCAI 2019.
  - The code is based on: Python 2.7 + pytorch 0.4.0.
  - You can run <AG_Net_path>/code/test.py for testing any new image directly.
  - You can run <AG_Net_path>/code/main.py for training a new model.

## Quick usage on your data:
  - Put your desired file in <AG_Net_path>/data/<your_file_name>.
  - Put the images in <AG_Net_path>/data/<your_file_name>/images.
  - Put the labels in <AG_Net_path>/data/<your_file_name>/label. The label must be *.png type
  - Divide data into training and test data, and store the image name in the train_dict.pkl file.
  - The train_dict.pkl should contains two dictionary: 'train_list' and 'test_list'.
