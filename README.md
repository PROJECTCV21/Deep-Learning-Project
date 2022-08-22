# AUTOMATED CARDIOTHORACIC RATIO CALCULATION AND CARDIOMEGALY DETECTION USING IMAGE PROCESSING AND DEEP LEARNING
AUTOMATED CARDIOTHORACIC RATIO CALCULATION AND CARDIOMEGALY DETECTION USING IMAGE PROCESSING AND DEEP LEARNING

Cardiomegaly is enlargement of heart, this may cause due to thickening of heart muscles that results in difficulty in pumping of blood. Chest x-ray is usually conducted in order to diagnose abnormal conditions in the chest and nearby structure. From chest X-ray, CARDIOTHORACIC RATIO (CTR) is calculated to identify the enlargement. In this study, CTR is automatically calculated by using traditional image processing, Along with deep learning model. The result indicates the feasibility of developing computer-aided diagnosis systems for cardiomegaly from X-ray is acceptable.

X-ray images are widely used for detection of cardiomegaly, we have used 3 different datasets. As we used two approaches traditional as well as deep learning based.
- Traditional Approach:
In this CTR is calculated using 2 steps, i.e. lung segmentation and CTR calculation using Distance considering 1 pixel as 1 unit. Lung segmentation is done by using a pretrained model known as ResNet34 [^1]. 
- Deep Learning Approach:
For Deep learning, CNN model with 5 layers is used. Relu as activation function at each layer and sigmoid at last layer is used.
- Dataset:
3 different dataset are used to test model i.e. two dataset from kaggle [^2] and NIH Chest-Xray14 [^3].
- Result:
The model on NIH data from kaggle shows better result then already proposed. 
[^1]:https://github.com/alimbekovKZ/lungs_segmentation/
[^2]: https://www.kaggle.com/code/rahimanshu/cardiomegaly-x-ray-using-alexnet/data
[^3]: https://nihcc.app.box.com/v/ChestXray-NIHCC/folder/37178474737
