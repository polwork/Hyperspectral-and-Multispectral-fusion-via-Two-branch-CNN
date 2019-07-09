This is the implementation code of paper"

Yang, J., Zhao, Y. Q., & Chan, J. (2018). Hyperspectral and multispectral image fusion via deep two-branches convolutional neural network. Remote Sensing, 10(5), 800.

yang123jx@mail.nwpu.edu.cn

Steps
1. Put the prototxt in examples folder of caffe, training the caffemodel
2. Put the caffemodel in matlab\fusion folder, and run "saveFIlters_fusion.m", caffemodel could be read in matlab
3. Run "main.m" in matlab, you could reconstruct HR HSI in matlab. 

Notes: The recostruction of HR HSI is implemented in matlab, which is more clear, but the running time would be long since there is no GPU here.
