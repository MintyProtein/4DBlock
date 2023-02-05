# 4DBlock
데이콘 4D block 경진대회 (2023.01.02 ~ 2023.01.30, private 13th)

## File Structure
```
├── README.md
├── indoorCVPR_09.tar
├── open.zip
├── preprocess.ipynb
├── sample_submission.csv
└── train.ipynb
```
indoorCVPR_09.tar

-download from https://web.mit.edu/torralba/www/indoor.html



open.zip 

-dowload from https://dacon.io/competitions/official/236046/data

## Train Process
1. Download indoorCVPR_09.tar & open.zip from the link above, and unzip it
2. Run preprocess.ipynb to generate background-removed block image
3. Run train.ipynb
The model's pth file will be saved in `./checkpoints`, and the submission file will be saved in `./submissions`
