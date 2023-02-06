# Masked Face Generation
This project aims to generate high-resolution images of faces without masks, using Generative Adversarial Networks (GANs). The model is trained on a dataset of celebrity faces, with the goal of having the model learn to generate faces that are similar to those in the training set. The output images are intended to look like faces, although the quality of the generated images will depend on the quality and diversity of the training data.

### Requirements
Python 3.7 or higher
PyTorch 1.6.0 or higher
NumPy
Matplotlib
TensorBoard
TensorFlow (optional, for TensorBoard)

### Setup
1. Clone the repository to your local machine
$ git clone https://github.com/<username>/masked-face-generation.git
$ cd masked-face-generation
 
2. Download the celebrity face dataset (or use your own dataset) and place it in the data directory
    
### Usage
  
1. Train the model
$ python train.py --data_dir=data --model_dir=models

2. Generate new faces
$ python generate.py --model_dir=models --num_images=10 --output_dir=output

  
### Results
The generated faces can be found in the output directory. The TensorBoard logs will be stored in the models directory.
 

### Limitations
- The quality of the generated faces may be limited by the quality and diversity of the training data.
- Generating high-resolution images can be computationally expensive and may require significant amounts of time and computing power.
- The model may struggle to generate faces that are significantly different from those in the training set.
  
  
### Contributing
Contributions are welcome! If you would like to contribute to the project, please follow these steps:

1. Fork the repository
2. Create a new branch for your changes
3. Make your changes
4. Submit a pull request
  
### License
This project is licensed under the MIT License.
