# Research-Papers-Implementation

This repository contains the paper implementations various advanced CNN based architectures. The primary goal of this repository is to show how to implement these papers using `tensorflow-keras`. Model performance and accuracy are not taken into consideration while implementing these papers. I just focused on the implementation part.

For the implementation I used `facial emotion` datset. The reason for not opting other well known datsets like `MNIST` is due the fact that those datasets are fairly simple. Whereas `facial emotion recognition` aka `FER` is a bit complex task to do.

Currently I have implemented the below papers, for each paper I mentioned the link to the paper as well. Also I didn't exactly mimiced the architecture bcz they are very deep and are usually designed for images with larger sizes like in `imagenet` but the dataset I used is of size `48x48` which is aroud 5 times smaller then imagenet. Hence instead of using the same number of layers as mentioned in the paper I just decreased the number of layers. But the model architecture is exactly same and if you wish you can play by adding more and more layers, it's really easy to do in my code.

I have implemented each paper in seperate `google-colab` (to leverage free gpu). For Each paper I mentioned the `link to the paper`, `notebook in this repository` and `colab notebook` as well. You can directly read the notebooks in this repository but if you face problem while rendering jupyter notebooks in github(which you may) then directly open the colab link.

### Papers Implemented

1. DenseNets<br>
        paper - https://arxiv.org/abs/1608.06993v3<br>
        notebook - https://github.com/greatsharma/Research-Papers-Implementation/blob/master/DenseNet.ipynb<br>
        colab - https://colab.research.google.com/drive/1qjUdDKxAIdpMHc9by81XTWp9ZNzyuJQc#scrollTo=1q6LyJOZm9c4<br>
        
2. GoogLeNet / InceptionNet<br>
        paper - https://arxiv.org/abs/1409.4842<br>
        notebook - https://github.com/greatsharma/Research-Papers-Implementation/blob/master/InceptionNet.ipynb<br>
        colab - https://colab.research.google.com/drive/1FNUTbp9735lRMWQYempPEhgbhfmEBbCP#scrollTo=eIEtviGCnZan<br>

3. ResNet<br>
        paper - https://arxiv.org/abs/1512.03385<br>
        notebook - https://github.com/greatsharma/Research-Papers-Implementation/blob/master/ResNet.ipynb<br>
        colab - https://colab.research.google.com/drive/1NW42aw5f83TA-AyADs-yY1BdzV35PAcK#scrollTo=vS1PyWprhI18<br>

4. XceptionNet<br>
        paper - https://ieeexplore.ieee.org/document/8099678<br>
        notebook - https://github.com/greatsharma/Research-Papers-Implementation/blob/master/XceptionNet.ipynb<br>
        colab - https://colab.research.google.com/drive/1Bo92DVpz1KyYPTCdC3neGbj8wJFdks0o#scrollTo=wX_mi-p4h2vK<br>

5. U-Net<br>
        paper - https://arxiv.org/abs/1505.04597<br>
        notebook - https://github.com/greatsharma/Research-Papers-Implementation/blob/master/denoising_Unet.ipynb<br>
        colab - https://colab.research.google.com/drive/1MmS_b3u46WsAs_gDrFm5Vci2II-SA68t#scrollTo=tOe8w59LlsUp<br>
