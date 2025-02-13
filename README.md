# Periaortic_fai

## Overview
Periaortic_fai automates the process of recognizing the aorta in CT images, tracing the vessel wall, and measuring the average CT value of adipose tissue beyond the vessel wall.


## Usage
This project uses a pretrained model.  
The model can be downloaded from the `GitHub Releases` section of this repository.

1. Download the pretrained model(model_final.pth) from [latest release page](https://github.com/Sho-N/periaortic_fai/releases/latest).
2. Place the program and model file in the MyDrive folder on Google Drive.
3. Run without any installation by using [Google Colaboratory](https://colab.research.google.com/).



## Requirements
Periaortic_fai is based on [Detectron2](https://github.com/facebookresearch/detectron2).
* Detectron2 (0.6)
* Python (3.11)
* Pytorch (2.5)
* pydicom (3.0.1)
* pylibjpeg (2.0.1)
* pylibjpeg-libjpeg (2.3.0)


## Directory Structure
```
MyDrive/Periaortic_fai/
  ├── input/                         # Input data
  │  ├─folder1                       # CT folders
  │  │  └─*.dcm                      # DICOM files
  │  ├─folder2
  │  └─folderN
  ├── output/                        # Results
  ├── weights/                       # Trained weights of model
  │  └─mask_rcnn_X_101_32x8d_FPN_3x_20240513
  │      └─model_final.pth           # Pretrained model
  └── AortaDetector_predict.ipynb    # Main program
```

## License
Periaortic_fai is licensed under the [Apache 2.0 license](LICENSE).

---
✏️ **[Periaortic_fai]** by [ShoN]
