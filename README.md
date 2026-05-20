# Facial Recognition Demo using Keras

This repository contains a simple facial recognition demo built with TensorFlow/Keras

The goal of this demo is to show a basic deep learning pipeline for face classification, including data loading, preprocessing, transfer learning, training, evaluation, and visualization.

## Project Overview

This project uses the Labeled Faces in the Wild (LFW) dataset and trains a transfer learning model to classify face images into one of several known identities.

The model uses MobileNetV2 pretrained on ImageNet as a feature extractor, followed by custom classification layers.

This demo is intended for educational purposes and is not a production-level biometric system.

## Dataset

Dataset used: **Labeled Faces in the Wild (LFW)**

The dataset is loaded directly using scikit-learn

## Required Libraries

tensorflow scikit-learn matplotlib numpy
