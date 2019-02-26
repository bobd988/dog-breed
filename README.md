
## Project Overview

Dog Breed Classification using the PyTorch with CNN first and then improve the accuracy with transfered learning with Resnet.


## Project Instructions

### Instructions


1. The required dataset is not included. You will need to download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).  Unzip the folder and place it in the repo, at parent location of the project.  The `dog_images/` folder should contain 133 folders, each corresponding to a different dog breed.
2. The required dataset is not included. You will need to download the [human dataset](http://vis-www.cs.umass.edu/lfw/lfw.tgz).  Unzip the folder and place it in the repo, at parent location of the project.  If you are using a Windows machine, you are encouraged to use [7zip](http://www.7-zip.org/) to extract the folder. 
3. Make sure you have already installed the necessary Python packages according to the README in the program repository.
4. Open a terminal window and navigate to the project folder. Open the notebook and follow the instructions.
	
	```
		jupyter notebook dog_app.ipynb
	```

5. If the trainning takes too much time consider using GPU supported pytorch version. 
	```
		conda install -c anaconda pytorch-gpu
	```
6. Make sure training machine has GPU hardware by running that use command.
	```
		nvidia-smi
		python -c 'import torch; print(torch.rand(2,3).cuda())'
	```
	If the first one fails, your drivers have some issue, or you dont have an (NVIDIA) GPU

	If the second fails, your pytorch instalaltion is not able to contact the gpu for some reason. For example the #5 command has not run yet. 
