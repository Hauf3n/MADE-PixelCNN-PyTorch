# MADE-PixelCNN-Pytorch

[MADE](https://arxiv.org/abs/1502.03509) paper Implemenation with [PixelCNN](https://arxiv.org/abs/1601.06759) as an auxiliary input.
Used on coloured MNIST dataset, which is used for adversarial training.

# Results

The loss decreased by a factor of 2x using MADE+PixelCNN rather than just using [my PixelCNN Implementation](https://github.com/Hauf3n/PixelCNN-Pytorch-coloured-MNIST).
The numbers got a bad shape, but one can see the improvements in the background
and there are no longer noisy pixels around the number shapes.   

![results](https://github.com/Hauf3n/MADE-PixelCNN-Pytorch/blob/master/images/made_pixelcnn.png)

# Improvments
- increase batch size
- larger model
- maybe different MADE colour channel ordering
...
