# Project-deep-learning
# The project title" Object Detection in Hazardous Environment".
## Authors
## Team members
- [@ragadalhejaily](https://www.github.com/ragadalhejaily)
- [@rahafalhejaily](https://www.github.com/rahafalhejaily)
- [@Maie667](https://www.github.com/Maie667)
- [@ShareefahAlessa](https://www.github.com/ShareefahAlessa)
-  AlWasemah Alanzi.
## Dataset
### DAWN (Detection in Adverse Weather Nature) dataset
The DAWN dataset includes a set of 1,000 images of real traffic environments, which are divided into four groups of weather conditions: fog, snow, rain and sandstorms. It has annotations using object bounding boxes for autonomous driving and video surveillance scenarios.
- The dataset at Link: https://data.mendeley.com/datasets/766ygrbt8y/3
- data pre-proccessing: We modified the mistakes we found in the annotated files for each image and split the dataset into 75% train,15% val,10% test.
## Proposed Model
### Yolov5 model
- We train the YoloV5s detector on the our dataset to detect and locate the object in image.
- the dataset At [folder DAWN_holdoutV2](https://drive.google.com/drive/folders/15CbWMwl-L_YFbPzjDluJBRAqmIFPnrLf?usp=sharing)

## Running the code
Run the code :  `python main.py --videos path of video`

## Demo
#https://user-images.githubusercontent.com/24452519/170476371-b7192762-b562-4d23-bf27-ae5ad11251b3.mp4


