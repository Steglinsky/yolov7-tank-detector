
# yolov7-tank-detector

The goal of this project is to create an AI model based on YOLOV7 for real-time optical recognition of tanks. 

 **Main objectives:**
1. The model should detect tanks regardless of their orientation in space.
2. The model must not mark civilian vehicles as tanks. 
3. The model is to mark tanks with the highest possible accuracy regardless of optical masking.

 **Additional objectives:**
1. The model should recognize the type of the targeted machine.

**Resources used:**
1. https://github.com/WongKinYiu/yolov7
2. https://www.kaggle.com/datasets/antoreepjana/military-tanks-dataset-images


# Change-log

### Experiment #2
| Note|Improved learning set size  |
|--|--|
|Epochs  | 30 |
| Learning set size | 100 |
| Test set size |  15|
| Precision |   0.754|
---
### Experiment #1
| Note | Test run after environment configuration |
|--|--|
|Epochs  | 3 |
| Learning set size | 30 |
| Test set size |  10|
| Precision |   0.1797|

