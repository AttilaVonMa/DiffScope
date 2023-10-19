# Perceptual loss for physics informed neural network image reconstruction for diffuser endoscopy DiffScope
That is a Project of „Photonische Messsystemtechnik“ in TU Dresden.
The Motivation of the Project :
Diffuser based imaging is a recent topic in computational optics. The diffuser generates a unique pseudorandom speckle pattern for every point within a volumetric field-of-view on an image plane. By solving the inverse problem, the 3D scene can be reconstructed fast computationally by using neural networks. In conjunction with imaging waveguides, this enables the realization of single shot 3D microendoscopes.
For the training of image-reconstructing networks, choosing a fitting loss function is crucial. In generative adversial networks (GAN), two neural networks are trained to contest with each other where one (Generator) is generating images from noise while the other one (Discriminator) tries to discriminate these images from real ones. This concept can also be adapted for an image reconstruction task where the discriminator network acts as a perceptual loss function for the reconstruction network, which generates images from measurements instead of noise.

The Tasks :
1.Implementation of a Wiener-filter-based physics-informed neural network for image reconstruction in Python
2.Realization of a GAN structure for perceptual loss function
3. Comparison to conventional loss function

