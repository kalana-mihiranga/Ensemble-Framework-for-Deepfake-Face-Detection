# Ensemble-Framework-for-Deepfake-Face-Detection

## Overview

Deepfake face generation techniques have advanced rapidly, posing increasing risks to biometric verification systems that rely on facial recognition for secure authentication. While many deepfake detection models achieve high performance on benchmark datasets, their ability to generalize across unseen generation methods remains limited. In this work, we propose a heterogeneous ensemble framework that integrates spatial convolutional analysis, frequency-domain artifact detection, and patch-level localized inspection to improve robustness across diverse deepfake generation families. The base detectors operate on complementary representation domains and are fused using a meta-learning strategy.

Experimental evaluation demonstrates statistically significant improvements over individual models within the primary dataset. However, cross-dataset evaluation reveals substantial performance degradation under distribution shift, highlighting persistent dataset bias in deepfake detection systems. Our findings emphasize the importance of ensemble diversity and robustness-oriented evaluation protocols in securing biometric systems against evolving deepfake threats.

## Getting Started

You can experiment with the framework using the provided Google Colab notebook:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/your-notebook-link-here)

Replace `your-notebook-link-here` with the actual URL of your Colab notebook once available.

## Structure

* `README.md` - Project description
* ...