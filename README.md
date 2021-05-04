# HDR_Computational_Photography
This repository is to save the files from the coding project to the Computational Photography class.

Maverick Lim                ID 
Vinícius Silvestre Lourenço ID 2020280042

hdr.py
  >Contains the original methods from the Recovering High Dynamic Range Radiance Maps from Photographs paper
  https://dl.acm.org/doi/10.1145/258734.258884

test_desktop.ipyn
  >Code created to be able to iterate through the new hdr images, ingest them, read the exposures in the TXT files and run the correct sequence of methods to create the HDR images

Flatten_flow.ipyn
  >Code created by the team as a new logic to process the images using vectorized logic instead of sequences of loops
  >New method to flatten the images
  >New method to separate the channels
  >New method to unflatten the images
  >Adjustment made to all methods to deal with flattened images instead of using loops on common ones
  >This code is working until the compute radiance map, there the dimension from the image vector generates an overload on the memory when doing a dot product

HDR Inputs folder
  > Each folder under HDR inputs is saving the group of images to be processed, a txt with informations about the pictures and the outputs from the HDR processing
