
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
The dataset was meticulously labeled, with each image annotated with the corresponding hand gesture class. This labeling process involved manual inspection and verification by the authors, ensuring accurate ground truth labels for training and evaluation purposes.
<img width="493" alt="Screenshot 2024-11-06 at 11 16 19 AM" src="https://github.com/user-attachments/assets/c699430a-c3d0-40f2-bc5d-e5753ebb56ac">


## Results


| Metric            | Value  |
|-------------------|--------|
| Training Loss     | 0.0201 |
| Categorical Accuracy | 0.9750 |
| F1 Score          | 0.9731 |
| Precision         | 1.0000 |
| Recall            | 0.975  |

<img width="474" alt="Screenshot 2024-11-06 at 11 16 33 AM" src="https://github.com/user-attachments/assets/fe8a671f-f24e-47cd-a8fa-ed4f943432f4">

## Acknowledgements

Funding: H. Thangaraj contributed to this work while undertaking a research collaboration with the Department of Computer Science, Vellore Institute of Technology under Professor Raju Patel.

Open Access: For open access purposes, the authors have applied a Creative Commons Attribution (CC BY) licence to any Author Accepted Manuscript version arising.

Data Access Statement: This study involves primary analyses of a custom curated dataset, that are described in the text.

## Appendix

**Note:** Please, when using any of the resources provided here, remember to cite this repository.

