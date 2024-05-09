# tls-wsi

## Setup

python 3.10

torch

openslide-python

For windows machines
[Windows Binaries](https://openslide.org/download/#windows-binaries)
[Importing OpenSlide](https://openslide.org/api/python/#basic-usage)

opencv-python

pandas

tifffile

imageio

matplotlib

Ali to add folder structure instructions here
## Folder Structure
1. 


train_data
-- train_patches
-- train_gt

val_data
-- val_patches
-- val_gt



## Running Code

### Prepare the data

(task) Ali to update the code to have one preprocssing script for extraciton of patches and lables/annotaitons from XML file

1. Setup path in the pre_processtrain.py and pre_processtest.py
2. Run ```python preprocess_train.py```

### Visualize the extracted data
(task)  - Aperio ImageScope

### Train the Model
Model archtecure
How to change model archtecure



### Run Inference

### Visualize the predictions
(tasks)
1. contours from JPGs to XML
2. Aperio ImageScope visuliazation