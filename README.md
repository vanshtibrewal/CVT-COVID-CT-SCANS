# CVT_COVID-CT-CNN collaboration space/data storage/presentation of findings
Note: There are no commits by my github profile because there was some error when the creators of the repo tried to add me as a collaborator, so I would write/edit the code and send it to one of them to push to github.

Please note:
1. master-data contains folders of all compiled COVID and NonCOVID CT images (excluding hold-out dataset)
2. split-data contains 70/15/15 random permutation train/val/test split of images located in master-data
3. "DenseNet121_Training_and_Evaluation.ipynb" contains full training and evaluation for best performing TL architecture

8/25/20
master-data/split-data
COVID: 2431 total, train: 1701, val: 365, test: 365
NonCOVID: 2166 total, train: 1516, val: 325, test: 325

HO-data (used for secondary testing purposes)
COVID: 211
NonCOVID: 150
