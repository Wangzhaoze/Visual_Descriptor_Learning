# Visual Descriptor Learning

[![GitHub stars](https://img.shields.io/github/stars/Wangzhaoze/UTN_Mobile_Robotics.svg)](https://github.com/Wangzhaoze/UTN_Mobile_Robotics/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/Wangzhaoze/UTN_Mobile_Robotics.svg)](https://github.com/Wangzhaoze/UTN_Mobile_Robotics/network)
[![GitHub issues](https://img.shields.io/github/issues/Wangzhaoze/UTN_Mobile_Robotics.svg)](https://github.com/Wangzhaoze/UTN_Mobile_Robotics/issues)


## 1. Introduction

This is the implementation of **Self-Supervised Dense Visual Descriptor Learning** based on Python. 

## 2. Acknowledge

####  2.1 Programming Framework: [Pytorch Lightning](https://lightning.ai/) & [Hydra](https://hydra.cc/)

<div align=center>
  <img src=".\docs\images\pl.jpg" alt="Image" width="400" higth='500'>,
  <img src=".\docs\images\hydra.png" alt="Image" width="400" higth='1000'>
</div>

<br>

**PyTorch Lightning** is an open-source lightweight framework for deep learning research, built on top of PyTorch, designed to simplify the development of training and research processes, and improve code readability and maintainability. PyTorch Lightning provides a set of high-level abstractions that help you organize, train, and evaluate deep learning models more easily.

**Hydra** is an open source software package for configuration management and optimization of application parameters. Its main goal is to help you organize and manage complex configurations more easily, making your code more scalable, reusable, and maintainable. Hydra is widely used in deep learning, machine learning, scientific computing, and other fields that require flexible configuration.

For more details of implementation and usage, you could see this: [Base_Framework_Pytorch_Lightning](https://github.com/Wangzhaoze/Base_Framework_Pytorch_Lightning)

####  2.2 Technical Background:

papers here

## 3. Contributes

- base
- callbacks
- backbones
- utils
- demo and usage

## 4. Structure

    |- base
    |   |- base_dataset.py
    |   |- base_dataloader.py
    |   |- base_datamodule.py
    |   |- base_model.py
    |   |- ...
    |
    |- callbacks
    |   |- PlotImgaePrediction.py
    |   |- ...
    |
    |- config
    |   |- template.yaml
    |   |- ...
    |
    |- data_module
    |   |- ...
    |
    |- docs
    |   |- tutorials
    |   |- ...
    |
    |- logs
    |   |- ...
    |
    |- models
    |   |- ...
    |
    |- unittests
    |   |- ...
    |
    |- utils
    |   |- ...
    |
    |- train.py


## 5. Usage
