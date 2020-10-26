# BokehramaEmulator
Jeff Manderscheid, Matriculation Number: 60037
Faculty of Electrical Engineering and Information Technology, Hochschule Karlsruhe
Bokehrama Emulation V1.0, 22.09.2020

The Bokehrama Emulation can create out of simple smartphone pictures with different sizes the associated Bokehramas. The directory to a folder containing images of the type JPG is the input.The standard input folder is the "images" folder already included. It contains several example pictures.

How to run:
Create a Conda environment with Python 3.7.
The requirements necessary to run can be found in the "requirements.txt".

The Bokehrama Emulation uses 2 Neural networks with pretrained models.

The semantic segmentation is done by the PSPNET_50 trained with ADE_20K dataset. The implementation from David Gupta
is available on Github:
https://github.com/divamgupta/image-segmentation-keras
Follow the instruction on the installation in the Github repository.

The depth estimation is realised by Monodepth2 which is also available on Github:
https://github.com/nianticlabs/monodepth2
"The associated Paper: Digging into Self-Supervised Monocular Depth Prediction" - by Godard, Clément; Aodha, Oisin Mac; Firman, Michael; Brostow, Gabriel
The Monodepth2 is already integrated in the Bokehrama Emulation Software, unlike the segmentation no installation is needed.

For further information on the Software take a look at the associated Thesis:
"A Bokehrama based on a Monocular Smartphone Image - Recreation of the Brenizer Method through Image Processing Using Neural Networks" - by Jeff Manderscheid
