# Research-Papers-Implementation

This repository contains the paper implementations of various advanced CNN based architectures. The primary goal of this repository is to show how to implement these papers using `tensorflow-keras`. Model performance and accuracy are not taken into consideration while implementing these papers. I just focused on the implementation part.

For the implementation, I used the `facial emotion` dataset. The reason for not opting for other well-known datasets like `MNIST` is due to the fact that those datasets are fairly simple. Whereas `facial emotion recognition` aka `FER` is a bit complex task to do.

Currently, I have implemented the below papers, for each paper I mentioned the link to the paper as well. Also, I didn't exactly mimic the architecture because they are very deep and are usually designed for images with larger sizes like in `imagenet` but the dataset I used is of size `48x48` which is around 5 times smaller then imagenet. Hence instead of using the same number of layers as mentioned in the paper I just decreased the number of layers. But the model architecture is exactly the same and if you wish you can play by adding more and more layers, it's really easy to do in my code.

I have implemented each paper in separate `google-colab` (to leverage free GPU). For each paper, I mentioned the `link to the paper`, `notebook in this repository`, and `colab notebook` as well. You can directly read the notebooks in this repository but if you face problems while rendering jupyter notebooks in GitHub(which you may) then directly open the colab link.

### Papers Implemented

1. DenseNets<br>
        paper - https://arxiv.org/abs/1608.06993v3<br>
        notebook - https://github.com/greatsharma/Research-Papers-Implementation/blob/master/DenseNet.ipynb<br>
        colab - https://drive.google.com/file/d/1qjUdDKxAIdpMHc9by81XTWp9ZNzyuJQc/view?usp=sharing<br>
        
2. GoogLeNet / InceptionNet<br>
        paper - https://arxiv.org/abs/1409.4842<br>
        notebook - https://github.com/greatsharma/Research-Papers-Implementation/blob/master/InceptionNet.ipynb<br>
        colab - https://drive.google.com/file/d/1FNUTbp9735lRMWQYempPEhgbhfmEBbCP/view?usp=sharing<br>

3. ResNet<br>
        paper - https://arxiv.org/abs/1512.03385<br>
        notebook - https://github.com/greatsharma/Research-Papers-Implementation/blob/master/ResNet.ipynb<br>
        colab - https://drive.google.com/file/d/1NW42aw5f83TA-AyADs-yY1BdzV35PAcK/view?usp=sharing<br>

4. XceptionNet<br>
        paper - https://ieeexplore.ieee.org/document/8099678<br>
        notebook - https://github.com/greatsharma/Research-Papers-Implementation/blob/master/XceptionNet.ipynb<br>
        colab - https://drive.google.com/file/d/1Bo92DVpz1KyYPTCdC3neGbj8wJFdks0o/view?usp=sharing<br>

5. U-Net<br>
        paper - https://arxiv.org/abs/1505.04597<br>
        notebook - https://github.com/greatsharma/Research-Papers-Implementation/blob/master/denoising_Unet.ipynb<br>
        colab - https://colab.research.google.com/drive/1ubWe7wj_K7_qGDostLnzP7Wf4DYqhgN6?usp=sharing<br>


If you face any problem while rendering notebook in github or opening in colab then please try it 3-4 times and if the situation remains the same then simply open an issue, I will fix that.
