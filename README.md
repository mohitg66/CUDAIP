# CUDAEnterpriseProject - CUDA NPP Filtering Lab

## Project Description

This project was developed as a platform for exploring various filtering and image processing capabilities of the CUDA NPP Library. It currently implements several filters, including the Canny Edge Detection Filter (also known as canny), the Sobel Edge Detection Filter (sobel), the Gauss Smooth Filter (gauss), and the Sharpening Filter (sharpen).

The project allows users to select an input image in BMP or PGM format, choose the desired filter, and specify the filename or directory for the output file. At present, the project supports processing only one image at a time due to an issue with NPP kernel execution, which fails when the same kernel is run multiple times. To run the project, a Coursera Lab environment is required, as it provides the pre-configured CUDA environment and eliminates the need for additional setup, which is beyond the scope of this project.

The project structure is based on the template from CUDA at Scale for the Enterprise Course Project Template.

## Code Organization

```bin/```
This folder should hold all binary/executable code that is built automatically or manually. Executable code should have use the .exe extension or programming language-specific extension.

```data/```
This folder should hold all example data in any format. If the original data is rather large or can be brought in via scripts, this can be left blank in the respository, so that it doesn't require major downloads when all that is desired is the code/structure.

```lib/```
Any libraries that are not installed via the Operating System-specific package manager should be placed here, so that it is easier for inclusion/linking.

```src/```
The source code should be placed here in a hierarchical fashion, as appropriate.

```README.md```
This file should hold the description of the project so that anyone cloning or deciding if they want to clone this repository can understand its purpose to help with their decision.

```INSTALL```
This file should hold the human-readable set of instructions for installing the code so that it can be executed. If possible it should be organized around different operating systems, so that it can be done by as many people as possible with different constraints.

```Makefile or CMAkeLists.txt or build.sh```
There should be some rudimentary scripts for building your project's code in an automatic fashion.

```run.sh```
An optional script used to run your executable code, either with or without command-line arguments.
