# Periaortic_fai

## Overview
Periaortic_fai automates the process of recognizing the aorta in CT images, tracing the vessel wall, and measuring the average CT value of adipose tissue beyond the vessel wall.


## Usage
1. Place in the MyDrive folder on Google Drive.
2. Run without any installation by using [Google Colaboratory](https://colab.research.google.com/).


## Requirements
Periaortic_fai is based on [Detectron2](https://github.com/facebookresearch/detectron2).
* Python3 (3.8.5)
* Pytorch (1.4.0)
* Torchvision (0.5.0)
* Fastai (1.0.61)


## Directory Structure
```
periaortic_fai/
├── input/                         # CT folders
│  ├─folder1                       # CT images
│  ├─folder2
│  └─folderN
├── output/                        # Results
├── weights/                       # Trained weights of model
└── AortaDetector_predict.ipynb    # Main program
```

## License
Periaortic_fai is licensed under the [Apache 2.0 license](LICENSE).

---
✏️ **[Periaortic_fai]** by [ShoN]
