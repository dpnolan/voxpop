# readme.txt

This is the runbook for the project code

[Code on GitHub.com/dpnolan/voxpop](https://github.com/dpnolan/voxpop)

[Input and output data on Google Drive](https://drive.google.com/drive/folders/1H7oVtb4p4dn21on6KVxUEnL4abff4e32?usp=sharing)

[Input and output data on Google Drive](https://drive.google.com/drive/folders/1H7oVtb4p4dn21on6KVxUEnL4abff4e32?usp=sharing)

# Documentation

pnol22154116.pdf

[Video Presentation on Google Drive](https://drive.google.com/drive/folders/1H7oVtb4p4dn21on6KVxUEnL4abff4e32?usp=sharing)

# Directory structure

## \voxpop 
Scripts should run in the home directory

## \ANT
## \DUB
Hold the input WAV files, 50-100 seconds of a single speaker reading out scripted sentences, the same for everyone
ANT and DUB subdirectories hold the recordings coming directly from SAIE in .wav format
Fed into the preprocessing scripts 

## sample_output_files 
Output from preprocessing scripts i.e. 
DataFrame pickles of personal data and the sound file, MFCC, MFCC delta and MFCC delta 2
Sample files are the WAV sound files coming from taking one second-long samples of the full speaker's sound recording

## Scripts

Requirements files are renamed with the Jupyter kernel they were extracted from 

## Pre DUB / ANTBEL $0 73$
Jupyter notebook with Python 
Preprocesing of the input files to produce the sample files and the DataFrame pickle files

## clustering12.ipynb
k-means clustering models 
Logistic regressions
Fed by the sample files and the pickle files

## EDA.ipynb
Exploratory Data Analysis
Fed by the sample files and the pickle files

## TF8 MLP.ipynb   
TF MLP Neural network 
Fed by the sample files and the pickle files

## TF10TK CNN.ipynb
TF CNN Convolutional neural network
Fed by the sample files and the pickle files

