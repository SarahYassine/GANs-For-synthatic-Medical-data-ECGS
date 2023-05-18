# GANs for Synthetic Medical Data Generation

## Overview
This project focuses on the utilization of Generative Adversarial Networks (GANs) to generate synthetic electrocardiogram (ECG) data. The dataset used is the "5000 ECGs" dataset, which contains normal and abnormal ECG signals. You can find the dataset here.

The primary objective of this project is to develop a GAN model consisting of a generator and discriminator. The generator aims to produce realistic ECG signals, both normal and abnormal, to address the scarcity of such data for medical research and projects.

## Features
Utilizes GANs to generate synthetic ECG signals.
Generates both normal and abnormal ECG data, addressing the limited availability of such data for medical research.
Evaluates the performance using two methods:
Encoder Reconstruction: Measures how well the model reconstructs ECG signals from the original dataset using Mean Squared Error (MSE) as the evaluation metric.
Neural Network Classification: Evaluates the generated data's classification accuracy (normal vs. abnormal) using a neural network trained on the original dataset

## Contributing
We welcome contributions to further enhance the project. To contribute, follow these guidelines:

1-Fork the repository and create a new branch for your contribution.

2-Make your modifications or add new features.

3-Write appropriate tests for the changes made.

4-Submit a pull request, clearly describing the changes and their purpose.

## Acknowledgments
We would like to express our gratitude to the following individuals and resources for their contributions and influence on this project:

The creators of the "5000 ECGs" dataset: PhysioNet
