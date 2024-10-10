# Helpful YOLOv8 Actions

This repository demonstrates helpful actions using YOLOv8. It includes functionality for loading a pre-trained model, performing training, continuing training after an early stoppage, performing inference, updating class labels, etc.

## Table of Contents
- [Overview](#overview)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Dataset](#dataset)
- [Contributing](#contributing)
- [License](#license)

## Overview
This notebook demonstrates how to:
- Training YOLOv8 models
- Multiple training options
- Resume training from checkpoints
- Model evaluation
- Inference from a pretrained YOLOv8 model
- Check labels of a pretrained YOLOv8 model
- Modify classes/labels
- Export the revised model

## Prerequisites
- Python 3.10 or later
- Jupyter Notebook environment / Kaggle / Google Colab
- GPU support (recommended for training)
  
## Installation
1. Clone this repository:
   ```
   git clone https://github.com/SakibAhmedShuva/Helpful-YOLOv8-Actions.git
   cd Helpful-YOLOv8-Actions
   ```
2. Install the required dependencies:
   ```
   pip install ultralytics
   pip install roboflow
   pip install -U ipywidgets
   ```
   
## Dataset
The notebook uses a custom dataset from Roboflow. The dataset is automatically downloaded using the Roboflow API during execution.

## Contributing
Contributions to this project are welcome. Please follow these steps to contribute:
1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature-name`)
3. Make your changes and commit them (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin feature/your-feature-name`)
5. Create a new Pull Request

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
