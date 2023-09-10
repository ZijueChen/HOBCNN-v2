# HOBCNN-v2

## Description

This project presents HOB-CNNv2, a regression deep learning vision model fine-tuned for detecting continuous tree branches under substantial natural occlusions experienced during summer. Building upon our preceding work detailed in the HOB-CNN paper (HOB-CNN: Hallucination of Occluded Branches with a Convolutional Neural Network for 2D Fruit Trees, https://doi.org/10.1016/j.atech.2022.100096), this iteration innovates in several significant ways, setting a new standard in the field.

### Key Features and Findings:

- **Superior Performance in Extreme Conditions**: The HOB-CNNv2 showcases remarkable accuracy in detecting tree branches even in heavily and extremely occluded conditions, standing distinctly ahead of the prevailing U-Net semantic segmentation model in evaluating branch position and thickness.

- **Pioneering Solution for Extreme Occlusions**: To the best of our knowledge, HOB-CNNv2 is the inaugural vision model crafted explicitly to address the challenges posed by extreme tree occlusions.

- **Dual Input Strategy for Enhanced Accuracy**: Our research divulged that the model’s performance peaks when utilizing both winter and summer images of the same tree as separate inputs for feature extraction. This strategy suggests that while the winter images aid in assimilating structural information, the summer counterparts contribute towards pinpointing exact positions.

### Detailed Insights:

For an in-depth understanding of the project including insights into the dataset, model structure, and evaluations, we recommend referring to our comprehensive paper titled "HOB-CNNv2: Deep learning based detection of extremely occluded tree branches and reference to the dominant tree image".

We sincerely believe that the advancements incorporated in HOB-CNNv2 pave the way for more nuanced and accurate tree branch detection, opening new avenues in the relevant research areas.


## Installation


### Prerequisites

- Python 3.9
- Tensorflow 2.6.0
- CUDA 11.2

### Setup

```sh
# Clone the repository
git clone https://github.com/ZijueChen/HOBCNN-v2.git

# Navigate to the project directory
cd HOB-CNNv2

# Install the required packages
pip install -r requirements.txt
