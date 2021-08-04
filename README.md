# Typhoon Intensity Prediction
Official source code for paper 《SAF-Net: A Spatio-Temporal Deep Learning Method for Typhoon Intensity Prediction》

## To run the code please kindly follow the steps below

* Step 1. Install the requirement environment 
```
pip install requirements.txt
```  
---

* Step 2. Download the require u and v component wind speed reanalysis data from ERA-Interim offical site
<https://apps.ecmwf.int/datasets/data/interim-full-daily/levtype=sfc/>
or download the preprocessing data from my google drive
<https://drive.google.com/drive/folders/1jxgoTwUjIELgoTHPiyT183UTIvOY6vU3?usp=sharing>

---

* Step 3. When the download process finishes, pleas put the files into the directory **./data/ERA_Interim/**

---

* Step 4. Run the jupyter notebook **3D_Typhoon_Structure_Constructed_In_Time_lots.ipynb** in the ERA_Interim folder to construct the 3D typhoon structure in time-lots

---

* Step 5. Finnaly, you can run the main jupyter notebook **SAF-Net.ipynb**

## Overall Architecture of SAF-Net

![image](https://github.com/xuguangning1218/TI_Prediction/blob/master/figure/Model.png)
