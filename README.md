# pointnet

To run the code, first downlaod and generate the datasets.

Run the functions in dataset.py to process data for both ModelNet40 and ShapeNet.

Training and evaluations for classication and part segmenation are performed in trainClassification.ipynb and trainPartSeg.ipynb, respectively. Note that due the small size of the ModelNet40, the entire dataset is first processed and saved to binary, wheares the data in ShapeNet are loaded from disk and processed on-the-fly during training. 
