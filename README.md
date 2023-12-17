# Face-Recognition-for-Holistic-Effect

## Project Overview

This project is an extension of the groundbreaking research conducted by Dobs et al. in their paper titled "Using deep convolutional neural networks to test why human face recognition works the way it does."

### Holistic Effect

The Holistic Effect is a captivating phenomenon wherein humans utilize relative distances and relationships between various facial features to recognize a face. Our project aims to delve into the origins and implications of this intriguing aspect of human face recognition.

### Hypothesis

We propose the hypothesis that the Holistic Effect emerges as a result of the optimization of humans for the specific task of face recognition.

## Experimental Procedure

To investigate our hypothesis, we followed a carefully designed experimental procedure:

1. **Model Training**: Two CNN models were trained for comparison. The first model, `CNN_face`, was exclusively trained on face images. In contrast, the second model, `CNN_object`, was trained on a mix of face images and general object images, including sofas, tables, and cars. Notably, the second model was not exclusively optimized for face recognition, as it had to recognize a variety of objects during training. Both models had an equal quantity of face images available for training.

The experimental design aimed to discern the role of face recognition optimization in the emergence of the Holistic Effect.

## Repository Structure

The project repository is organized for clarity and ease of use:

- **data**: Contains datasets used for training the CNN models.
- **code**: Encompasses implementation code for training CNNs, conducting experiments, and analyzing results.
- **results**: Houses the outcomes of experiments, including performance metrics, visualizations, and comparative analyses.

## Usage Guidelines

To replicate and expand upon our experiments:

1. Clone the repository: `git clone https://github.com/abhayp2204/Face-Recognition-for-Holistic-Effect.git`
2. Navigate to the code directory
3. Run the file `vgg.ipynb`