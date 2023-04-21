# Implementation-of-ViT-from-Scratch-for-MNIST-Classification
The implementation of the Vision Transformer for MNIST classification uses an image size of 224 x 224 x 3, with a patch size of 16 x 16, a hidden size (latent vector) of 128, 12 attention heads, and 12 transformer layers. The model is trained using the Adam optimizer with a learning rate of 1e-3, weight decay of 1e-5, and a batch size of 32 for 20 epochs. The resulting **test accuracy is 95.86%, with a loss of 0.1337**. </br>

1. `Image Size : 224 x 224 x 3`
2. `Patch Size : 16 x 16`
3. `Hidden Size : 128`
4. `Number of attention heads : 12`
5. `Number of transformer layers : 12`

While Convolutional Neural Networks (CNNs) have been proven to achieve high accuracy on the MNIST dataset, which consists of 28x28 grayscale images of handwritten digits, it is worth noting that Vision Transformers have shown impressive performance on other image classification tasks, particularly on large-scale datasets where they have outperformed traditional CNNs. **Therefore, while it is unlikely that Vision Transformers will significantly outperform CNNs on MNIST due to the dataset's simplicity and small size, it's still an interesting approach to explore**.

### Reference
1.[Image classification with Vision Transformer]( https://keras.io/examples/vision/image_classification_with_vision_transformer/)
2. [Vision Transformer in Tensorflow](https://dzlab.github.io/notebooks/tensorflow/vision/classification/2021/10/01/vision_transformer.html)
3. [An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale](https://arxiv.org/abs/2010.11929)
