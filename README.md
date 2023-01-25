# TPU_tfrDataset_With_TF_Keras
Solved this problem Implementing tensor-flow and keras. 
TPUs are powerful hardware accelerators specialized in deep learning tasks. They were developed (and first used) by Google to process large image databases, such as extracting all the text from Street View. This was kaggle competition where I tried exploring, knowing and implementing TPU's. 

### About the Dataset - 
• We're classifying 104 types of flowers based on their images drawn from five different public datasets. Some classes are very narrow, containing only a particular sub-type of flower (e.g. pink primroses) while other classes contain many sub-types (e.g. wild roses)

• The TFRecord format is a container format frequently used in Tensorflow to group and shard data data files for optimal training performace

• Each file contains the id, label (the class of the sample, for training data) and img (the actual pixels in array form) information for many images

• Dataset obtained from Kaggle is already divided into train, test and validation folders (train/*.tfrec, val/*.tfrec, test/*.tfrec) 

• Dataset obtained from Kaggle

### Project Overview-
• The dataset contains imperfections - images of flowers in odd places

• Build a classifier to classify the flower belonging to different groups/ class/ variants 

• read rhe images files and explored all different classes

• Used tensorflow and keras to solve this classification problem

• Successfully acheived 99% accuracy

### Images in dataset - 
![image](https://user-images.githubusercontent.com/111883941/214493549-84fd81ce-83a1-42f1-b957-96238c968b76.png)


