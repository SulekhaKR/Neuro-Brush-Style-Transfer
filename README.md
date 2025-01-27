# NeuroBrush: Style Transfer

A Neural Style Transfer project leveraging deep learning techniques to merge the content of one image with the artistic style of another. This implementation is based on pre-trained deep convolutional neural networks and uses advanced algorithms to create stunning visual transformations.

---

## Features

- **Content and Style Image Input**: Specify a content image and a style image.
- **Artistic Transformation**: Combine the structure of the content image with the artistic essence of the style image.
- **Customizable Parameters**:
  - Adjust the balance between content and style representation.
  - Configure the number of iterations for optimization.
- **Output**: High-quality artistic outputs in PNG format.

---

## Technologies Used

- **Programming Language**: Python 3.8+
- **Deep Learning Framework**: PyTorch
- **Visualization Tools**:
  - `matplotlib` for displaying images.
  - `Pillow` for image manipulation.
- **Pre-Trained Models**: VGG19 for feature extraction.

---

## Prerequisites

- Python 3.8 or above
- Installed Python libraries:
  ```bash
  pip install torch torchvision matplotlib pillow
##Setup Instructions
-Clone the Repository:
 ```bash
  git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>

##Install all required libraries using pip:
pip install -r requirements.txt

##Run the Notebook: Open the Jupyter Notebook file (NeuroBrush Style Transfer.ipynb) in Jupyter Notebook or Jupyter Lab:
jupyter notebook NeuroBrush\ Style\ Transfer.ipynb

##Usage
Input Preparation:

Place your content image (e.g., content.jpg) and style image (e.g., style.jpg) in the working directory.
Notebook Execution:

Open the Jupyter Notebook and follow the instructions step by step.
Adjust parameters such as content weight, style weight, and the number of iterations to achieve the desired output.
Save the Output:

After running the notebook, the stylized image will be saved as output.jpg in the working directory.


### To Do:
1. Replace placeholder links (e.g., `<your-username>`, `<repo-name>`, email, and LinkedIn profile).
2. Add `requirements.txt` if it's not already created.
3. Include example images (`content.jpg`, `style.jpg`, and `output.jpg`) in the repository.






