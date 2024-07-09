# satellite-image-segmentor
A gradio ui based web app  hosted deep learning model to segment satellite images 
Here's a basic README file for your project:

---

# Semantic Segmentation of Aerial Imagery

This project demonstrates semantic segmentation of aerial imagery using deep learning techniques, specifically targeting satellite images.

## checkout the live project at:(https://huggingface.co/spaces/Prerak51/satellite_image_segmentor)

## Requirements
- Python 3.x
- Required library can be installed via `pip install tensorflow opencv-python patchify `


## Setup
1. Clone the repository:
   ```bash
   git clone (https://github.com/prerakpatel51/satellite-image-segmentor
   cd satellite-image-segmentor
   ```
   


2. Download the dataset from [Semantic Segmentation Dataset](https://www.kaggle.com/datasets/humansintheloop/semantic-segmentation-of-aerial-imagery).

## Usage
- Run the training to train the segmentation model.
- Adjust parameters in firstfile as needed for your dataset.
- Use `satellite_image_segmentor_gradio_ui` to make predictions on new aerial imagery.The  file contains a Gradio UI application for interactive image segmentation.

## Model Architecture
- The model architecture is based on a U-Net variant tailored for semantic segmentation tasks.
- Loss functions include Dice Loss, Jaccard Coefficient, and Focal Loss for optimal performance.

## Dataset
- The dataset used is the "Semantic Segmentation Dataset" available at `/kaggle/input/semantic-segmentation-of-aerial-imagery`.

## Credits
- Developed by Prerak Patel.
- Inspired by hardwork only😃.

---

This README provides a brief overview of your project, including setup instructions, usage guidelines, model architecture details, and credits. Adjust the content as per your specific project details and preferences.
