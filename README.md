# DENSE-INception-U-net-for-medical-image-segmentation

Application of DIUnet in Retinal fundus data set segmentation is implemented. 
https://doi.org/10.1016/j.cmpb.2020.105395 : paper is available here.
The model explained and used is a Dense inception model that uses a inception_residual block for better accuracy during training. 

![image](https://user-images.githubusercontent.com/58776709/123516826-b4792a00-d6bb-11eb-9b25-4dfa0c0e1fa0.png)

In this paper, a novel module is proposed by combining the in- ception module with dense connection and construct the network architecture based on the U-Net with the module. The analysis path and the synthesis path are both included in this network architecture, and these two paths are made up of four types of blocks: the Inception-Res block, the Dense-Inception block, the down-sample block, and the up-sample block. Three Inception-Res blocks, one Dense-Inception block, and four down-sample blocks make up the analytic path. Three Inception-Res blocks, one Dense-Inception block, and four up-sample blocks make up the synthesis pipeline. A single Dense-Inception block is deployed in the network's midsection, and this block has many more inception layers than the others.

# Inception-Res block:

![image](https://user-images.githubusercontent.com/58776709/123517942-6404cb00-d6c1-11eb-98bc-d2d404965279.png)


# Dense-Inception block :

![image](https://user-images.githubusercontent.com/58776709/123517984-8f87b580-d6c1-11eb-9c7a-8f6d9fc8c14b.png)


![image](https://user-images.githubusercontent.com/58776709/123517996-9f06fe80-d6c1-11eb-8e97-cba13bfd541d.png)


# Down-sample and Up sample block :

![image](https://user-images.githubusercontent.com/58776709/123518044-dc6b8c00-d6c1-11eb-9b0e-70b75c07fbc3.png)


### Experimantal Results (carried out over DRIVE dataset) as mentioned in this paper:

![image](https://user-images.githubusercontent.com/58776709/123518152-39ffd880-d6c2-11eb-9c99-f7429a49238f.png)


### I am giving .ipynb file where the model is implemented using (prerequisites)
    - Python 3.7
    - keras 2.2.5
    - tensorflow 2.5.0
    - numpy

### I run this program on TPU runtime provided by colab pro. 
