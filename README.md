
# Gesture-Based Home Automation System Using Hand Sign Recognition

This repository presents a novel hand sign controlled
home automation system that utilizes Google’s Mediapipe pre-trained architecture and integrated with MobilNetV2 CNN for real-time tagging using Computer Vision paradigms.




## Directory Structure

```
project_root/
├── dataset-annotated
│   ├── test/   
│   ├── train/     
|
├── mediapipe/
|   ├── gesture_recognizer.task
|   ├── gesture_recognizer.task2
│   └── livestream.py
|
├── MobilNetV2.ipynb
│   
│
└── requirements.txt

```
## Dataset

A custom curated gesture dataset is introduced comprising over 200 high-resolution images capturing a wide range of hand gestures. The dataset encompasses various
orientations, lighting conditions, and backgrounds, ensuring that the system can effectively learn and generalize patterns associated with different gestures.
The dataset was meticulously labeled, with each image annotated with the corresponding hand gesture class. This labeling process involved manual inspection and verification by the authors, ensuring accurate ground truth labels for
training and evaluation purposes.


## Results


| Metric            | Value  |
|-------------------|--------|
| Training Loss     | 0.0201 |
| Categorical Accuracy | 0.9750 |
| F1 Score          | 0.9731 |
| Precision         | 1.0000 |
| Recall            | 0.975  |

## Acknowledgements

Funding: H. Thangaraj contributed to this work while undertaking a research collaboration with the Department of Computer Science, Vellore Institute of Technology under Professor Raju Patel.

Open Access: For open access purposes, the authors have applied a Creative Commons Attribution (CC BY) licence to any Author Accepted Manuscript version arising.

Data Access Statement: This study involves primary analyses of a custom curated dataset, that are described in the text.

## Appendix

**Note:** Please, when using any of the resources provided here, remember to cite this repository.

