# A-Deep-Learning-Based-Cascading-Ensemble-for-Brain-Tumor-Segmentation-
Machine Learning Project
Architecture: Cascading Deep Learning Ensemble
In this project we aimed to segment brain tumors using deep learning. For our project we have created a cascading ensemble consisting of three different model. All the models are improvement of UNet architecture. All the models have one down-sample block, one bottleneck and one up-sample block.  However, within the blocks they are configured differently. We have taken the models that performed very well for our dataset. The input image size is used 512*512, as we have seen with this shape the performance is better. The configuration of three architecture is given below:
                             
The Proposed Ensemble: 
Our proposed model is sequentially trained ensemble. As we have used separate models to train sequentially, it is like cascading. The architecture of the model is built using the following procedure:                 
