# tourism-destination-image-identification
25 image classification categories covering all the tourism scenes are established, which can serve a foundation for future AI tourism vision research. This study contributes to existing literature by introducing intelligent automation framework to tourism big data research and advancing innovative methodologies of analyzing online destination photos.

1. Due to the large amount of picture data, only half of the pictures have been uploaded. Please download from the network disk.

link：

The effect of the model trained with half the pictures is slightly different from the original.

2. There are two directories for the downloaded images, one is the training set image data, and the other is the test set image data. Please store these two directories directly under the project directory.

3. Please use the code files in the project directory. 1 Data Preprocessing & save to npy.ipynb to digitize and standardize the original picture. You can set the picture size.

4. Please use the code file in the project directory 2 Multi-Label-Image-Classification with tansfer learning .ipynb for image transfer learning training. Note that you must first download the precompiled weights for imagenet migration learning.

5. Please use the code file 3 Multi-Label-Image-Classification using combined precompiled weights.ipynb in the project directory to train the combined transfer learning pre-compiled weight model and evaluate the model.



1、由于图片数据较多，只上传了了一半的图片，请从网盘下载。用一半的图片训练的模型效果与原文后有些差异。
2、下载的图片有两个目录，一个是训练集的图片数据，一个是测试集的图片数据，请将这两个目录直接存放在本项目目录下。
3、请使用项目目录下的代码文件 1  Data Preprocessing & save to npy.ipynb对原始图片进行数字化、标准化等处理，可以设置图片大小。
4、请使用项目目录下的代码文件 2 Multi-Label-Image-Classification with tansfer learning .ipynb 进行图片的迁移学习训练。注意要先下载imagenet迁移学习的预编译权重。
5、请使用项目目录下的代码文件3 Multi-Label-Image-Classification using combined precompiled weights.ipynb 进行组合迁移学习预编译权重模型的训练，模型的评估。

