# Implementation-of-ViT-from-Scratch-for-MNIST-Classification
Implemetation of Vision Transformer from Scratch for MNIST Classification 
</br> For the vision transformer implementation, the image size is set at 224 x 224 x 3, with patch size 16 x 16, hidden size (constant latent vector) D of 128, number of attention heads of 12 and number of transformer layers of 12. </br>
Image Size : 224 x 224 x 3 <br/>
Patch Size : 16 x 16
Hidden Size : 128
Number of attention heads : 12
Number of transformer layers  : 12
</br>

The model is trained with Adam optimizer with learning rate of 1e-3, weight decay of 1e-5, with batch size of 32 and number of epoch of 20. The test accuracy achieved is 95.86% and loss of 0.1337. In the case of the MNIST dataset, which consists of 28x28 grayscale images of handwritten digits, CNNs have been shown to achieve very high accuracy with relatively small and simple models. Due to the simplicity and small size of the dataset, it is unlikely that Vision Transformers would outperform CNNs by a significant margin. However, it is worth noting that ViT has shown impressive results on other image classification tasks, especially on large-scale datasets, where it has shown to outperform traditional CNNs.
