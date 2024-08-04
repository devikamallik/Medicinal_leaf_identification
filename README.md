# Medicinal_leaf_identification

--

## Overview

This project aims to identify medicinal plant leaves using a MobileNetV2 model for efficient image recognition. The frontend of the application is built with Streamlit to provide an interactive user interface for users to upload leaf images and receive classification results.
The dataset consist of only 30 different classes of plant leaf.

## Project Components

1. **Leaf Classification Model**: 
   - **Model Used**: MobileNetV2
   - **Purpose**: To identify leaf and its medicinal properties along with its common and scientific names .
   - **Features**: MobileNetV2 is a lightweight deep learning model designed for mobile and edge devices, offering a good balance between performance and computational efficiency.

2. **Frontend Interface**: 
   - **Framework Used**: Streamlit
   - **Purpose**: To provide a user-friendly web interface where users can upload leaf images and view classification results.
   - **Features**: Simple and intuitive design, real-time feedback, and easy-to-use for non-technical users.

## Getting Started

### Prerequisites

- Python 3.7 or higher
- `pip` for installing Python packages
- Basic knowledge of machine learning and web development

### Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/devikamallik/medicinal_leaf_identification.git
   cd medicinal_leaf_recognition
   ```

2. **Install Required Packages**

   It's recommended to create a virtual environment first. Here’s how you can do it:

   

   Then install the necessary packages:

   ```bash
   pip install -r requirements.txt
   ```

   `requirements.txt` should include necessary libraries like TensorFlow, Streamlit, and other dependencies.



### Running the Application

1. **Start the Streamlit App**

   Navigate to the project directory and run:

   ```bash
   streamlit run app.py
   ```

2. **Interact with the Application**

   - Open your browser and go to `http://localhost:8501` to access the Streamlit interface.
   - Upload an image of a leaf using the file uploader.
   - View the classification results which include the predicted plant class and additional information if available.

## Model Training and Evaluation

### Training

- **Dataset**: The model is trained on a dataset consisting of 30 classes of medicinal plant leaves.
- **Process**: The dataset is preprocessed, and the MobileNetV2 model is fine-tuned using transfer learning to adapt to the specific classes of leaves.

### Evaluation

- **Metrics**: The model’s performance is evaluated using accuracy, precision, recall, and F1-score metrics.
- **Validation**: Cross-validation and test set evaluations are performed to ensure robustness.

## Contributing

Contributions are welcome! If you have suggestions, improvements, or bug fixes, please create a pull request or open an issue.




## Acknowledgments

- **MobileNetV2**: For efficient and accurate image classification.
- **Streamlit**: For an easy-to-use web framework for machine learning applications.
- **Dataset Providers**: For providing the dataset of medicinal plant leaves
download link  for dataset :https://www.kaggle.com/datasets/vishnuoum/medicinal-plant-dataset-augmented.

---# medicinal_leaf_identification
# medicinal-leaf-identification
