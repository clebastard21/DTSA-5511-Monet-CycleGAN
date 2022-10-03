# Project Title

I’m Something of a Painter Myself Mini-Project for course DTSA-5511 Week 5

## Project description
A GAN consists of at least two neural networks: a generator model and a discriminator model. The generator is a neural network that creates the images. For our competition, you should generate images in the style of Monet. This generator is trained using a discriminator.

The two models will work against each other, with the generator trying to trick the discriminator, and the discriminator trying to accurately classify the real vs. generated images.

Your task is to build a GAN that generates 7,000 to 10,000 Monet-style images.

## Dataset Description
The dataset contains four directories: monet_tfrec, photo_tfrec, monet_jpg, and photo_jpg. The monet_tfrec and monet_jpg directories contain the same painting images, and the photo_tfrec and photo_jpg directories contain the same photos.

The monet directories contain Monet paintings. 

The photo directories contain photos. 

### Files
-monet_jpg - 300 Monet paintings sized 256x256 in JPEG format
-monet_tfrec - 300 Monet paintings sized 256x256 in TFRecord format
-photo_jpg - 7028 photos sized 256x256 in JPEG format
-photo_tfrec - 7028 photos sized 256x256 in TFRecord format
