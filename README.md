# Reults from current model:
___
Annotated cell count: 62
___
>![original heatmap](https://github.com/jeffock/ihc_cellcount_cytoplasmic/blob/master/README%20images/origin_h5_img1.png)
___
Predicted cell count: 60
___
>![model heatmap](https://github.com/jeffock/ihc_cellcount_cytoplasmic/blob/master/README%20images/predict_h5_img1.png)
___
Original image: cytokeratin 14 (KRT14) stain
___
>![original image](https://github.com/jeffock/ihc_cellcount_cytoplasmic/blob/master/README%20images/origin_jpg_img1.png)
___
Annotated cell count: 349
___
>![original heatmap](https://github.com/jeffock/ihc_cellcount_cytoplasmic/blob/master/README%20images/origin_h5_img6.png)
___
Predicted cell count: 507
___
>![model heatmap](https://github.com/jeffock/ihc_cellcount_cytoplasmic/blob/master/README%20images/predict_h5_img6.png)
___
Original image: cytokeratin 14 (KRT14) stain
___
>![original image](https://github.com/jeffock/ihc_cellcount_cytoplasmic/blob/master/README%20images/origin_jpg_img6.png)
___

Current model is base model with 600 epochs. 

# Step-by-Step:
___
`git clone <url>` to download the repository where url is this repo's url. 

(figure out how to implement make_dataset.ipynb here)

Add the .jpg files to Data/images/ and the .h5 & .mat files to Data/ground_truth/. 

A usable version without the need for annotated .mat files will be released when proper results are attained. 

Run through val.ipynb while editing file paths as needed. This will return the results. 