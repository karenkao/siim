# note

## 2021-08-19

發現: 有些圖的 box 由於來自 seg 的mask，有些病灶的部位會被框成 小小的 box(非常小 ex: 2-50 pixel)，使得一張圖片有多達10-20個 box ，跟醫生討論...所以要減少那些小框
- [ ] 補box 統計圖


## 2021-08-09

訓練的圖丟進去 images

訓練的圖的 label丟進annotation

寫好準備 data

補一下 data review

參考:

- https://www.kaggle.com/c/siim-acr-pneumothorax-segmentation/overview/siim-cloud-healthcare-api-tutorial
- https://www.kaggle.com/seesee/siim-train-test?select=train-rle.csv
