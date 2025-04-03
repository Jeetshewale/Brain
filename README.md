# BrnTmr
## Comparitive analysis of traditional ML models for Brain Tumor Detection against the Federated Learning Approach

This project aims to provide a comprehensive comparision between the performances of the traditional ML models and Federated Learning approaches for the Brain Tumor detection and recognition tasks. The models were trained for four different classes i.e. glioma, meningioma, no tumor and pituitiary. The models essentials helps to detect the existenceof a tumor and which one if there exists one.

## Dataset
The dataset used for this project consists of 7023 labeled images, balanced across four categories.

## Project Workflow
The project follows a well-structured workflow to ensure effective implementation. It begins with Data Preparations, which involves performing basic Exploratory Data Analysis on the images such as checking dimensions of the images, resizing the images accordingly, dtecting color models of the images and converting to defined color model as required, checking the distribution of the images in each class and finally distributing the images into train (70%), test(15%) and val(15%) splits. Following this, a custom CNN model is defined and trained achieving a test accuracy of 95.36%. Transfer Learning on ResNet18 is done achieving a test accuracy of 98.82%. 

## Getting Started

Follow these steps to clone the repository, install the required dependencies, and run the project.

### Clone the Repository
First, clone this repository to your local machine:
```bash
git clone https://github.com/darkbit404/BrnTmr.git
```
### Navigate to the Project Directory
Use cd command in windows terminal or windows powershell to navigate to the project directory.
```bash
cd BrnTmr
```
### Install Dependencies
Ensure you have Python installed, then install the required dependencies listed in the requirements.txt file:
```bash
pip install -r requirements.txt
```
### Run the project
Open the cloned repository in your preferred IDE (e.g., Jupyter Notebook, VSCode, or PyCharm). Locate and open the .ipynb file, and then execute the code cells to run the project.

---

## Outputs
