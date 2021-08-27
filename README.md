# acse_9_project

## Description
This project is implemented using Python 3 on Google's Colab. All models are trained using Colab's GPU.

## Content
dataset folder: Include all datasets used in this project. Files that has .xlsx format are generated synthetic data and csv files are the pollution dataset

_model folder: Contains all trained models for the pollution problem during the entire project. The best model (also used in the report) can be found in the following directory:

GAN's Generator: './pollution_dcgan_7d_model/generator_10000_50'
GAN's Discriminator : './pollution_dcgan_7d_model/discriminator_10000_50'

AAE's Encoder: './pollution_aae_7d_model/encoder_1000_50'
AAE's Decoder: './pollution_aae_7d_model/decoder_1000_50'
AAE's Discriminator './pollution_aae_7d_model/discriminator_1000_50'

## Notice before using
Since all codes are implemented using Colab, all training notebooks requires to mount the drive first before reading in data/model. So in order to run the notebook, either change the directory of models/data or change the path inside the notebook. 

## Report Results
All results shown in the report can be accessed in the notebook pollution_dcgan_7d.ipynb