# Virtual Try On

A deep learning project for virtual try-on of clothing using PyTorch. This project includes data preprocessing, pose prediction, and model training for clothing transfer on person images.

## Features
- Data preprocessing scripts
- Pose prediction
- Model training and testing
- Support for CUDA 11.8 (PyTorch 2.0.1)

## Setup
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Prepare your data in the `data/` and `Data_preprocessing/` folders as described in the documentation.

## Usage
- Run training:
  ```bash
  python train.py
  ```
- Run testing:
  ```bash
  python test.py
  ```

## License
See [LICENSE](LICENSE) for details.
