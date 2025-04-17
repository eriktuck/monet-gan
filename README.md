This notebook uses the CycleGAN generative adversarial network to stylize photos in the style of Monet as described in paper Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks.

Image-to-image translation tasks are easy for humans. Humans have no trouble imagining the scene that Monet painted as a true landscape, or vice versa. However, for machines this task is more challenging. Often there are no labeled examples for which to train a model (for example, a photograph and the resulting landscape painting). CycleGAN proposes an adversarial network that trains a generator to fool a discriminator that is trying to detect generated images. Over time, the generator learns the appropriate style to achieve the image-to-image translation task.

This notebook is meant to be run on Kaggle with GPU or TPU. Find it here: https://www.kaggle.com/code/erikanderson1/gan-for-generating-art-in-the-style-of-monet/
