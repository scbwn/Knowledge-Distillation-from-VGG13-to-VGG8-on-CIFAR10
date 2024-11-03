# Knowledge-Distillation-from-VGG13-to-VGG8-on-CIFAR10

## Project Overview

Implementation of knowledge distillation from VGG13 (teacher model) to VGG8 (student model) on the CIFAR10 dataset using TensorFlow.

## Features

- Knowledge distillation technique for model compression
- VGG13 (teacher) and VGG8 (student) architectures
- CIFAR10 dataset loading and preprocessing
- Custom implementation of knowledge distillation loss

## Implementation Details

- Framework: TensorFlow 2.x
- Dataset: CIFAR10 (60,000 32x32 color images)
- Teacher model: VGG13
- Student model: VGG8
- Knowledge distillation loss: combination of cross-entropy and Kullback-Leibler divergence
- Optimization: SGD optimizer with nesterov momentum and learning rate scheduling

## Requirements

- Python 3.x
- TensorFlow 2.x
- NumPy

## Usage

1. Clone repository
2. Install requirements
3. Download CIFAR10 dataset
4. Run training script
5. Evaluate student model performance on test dataset

## Example Use Cases

- Model compression for edge devices
- Knowledge transfer from large to smaller models
- Improving performance of smaller models

## References

- G. Hinton, O. Vinyals, and J. Dean, “Distilling the knowledge in a neural network,” in Proc.
NeurIPS Deep Learning and Representation Learning Workshop, 2015.
