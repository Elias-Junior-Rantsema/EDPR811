# EDPR811 - Automated Waste Sorting System

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![OpenCV](https://img.shields.io/badge/OpenCV-4.x-green.svg)](https://opencv.org/)
[![Status](https://img.shields.io/badge/Status-In%20Development-orange.svg)]()

## Engineering Design and Research Project

**Multi-Sensor Fusion for Automated Recyclable Material Classification**

This repository contains the design, implementation, and research documentation for an automated waste sorting system that uses multi-sensor fusion technology to classify and sort recyclable materials (glass, metal, plastic, and paper) with high accuracy and cost-effectiveness.

## Project Overview

The system employs a **multi-sensor fusion** architecture that integrates:

- **Computer Vision** (RGB camera + machine learning)
- **Inductive Sensors** (metal detection)
- **Capacitive Sensors** (dielectric constant measurement)

## Hardware Components

| Component             | Specification                | Purpose                |
| --------------------- | ---------------------------- | ---------------------- |
| **Raspberry Pi 4B**   | 4GB RAM, Ubuntu 22.04        | Main processing unit   |
| **Camera Module**     | 8MP, 1080p, CSI interface    | Computer vision        |
| **Inductive Sensor**  | M18, 8mm range, NPN          | Metal detection        |
| **Capacitive Sensor** | M18, 15mm range, analog      | Dielectric measurement |
| **Arduino Nano**      | ATmega328P, USB              | Sensor interface       |
| **Conveyor System**   | Variable speed, 500mm length | Material transport     |

## Software Stack

- **Operating System**: Ubuntu 22.04 LTS (Raspberry Pi)
- **Computer Vision**: OpenCV 4.x, YOLOv5-nano
- **Machine Learning**: PyTorch, TensorFlow Lite
- **Sensor Interface**: Arduino IDE, Python serial
- **Control System**: Python 3.8+, GPIO libraries

---

_This project is part of the EDPR811 Engineering Design and Research Project course, demonstrating practical application of multi-sensor fusion technology for automated waste sorting systems._
