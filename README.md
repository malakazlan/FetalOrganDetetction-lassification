# Fetal Organ Detection Classification

A web application that uses deep learning to classify fetal ultrasound images into different organ categories. This project is based on extensive research in healthcare and medical imaging, specifically focusing on fetal organ detection and classification.

## Research Background

This project is built upon extensive research in healthcare and medical imaging, specifically focusing on fetal organ detection and classification. The model uses a pre-trained deep learning architecture that has been fine-tuned on a comprehensive dataset of fetal ultrasound images.

### Research Papers

We have selected the following research papers as the foundation for our project:

1. **"Transfer learning for accurate fetal organ classification from ultrasound images: A potential tool for maternal healthcare providers"**
   - Published: October 20, 2023
   - Source: PMC PubMed Center
   - URL: https://www.nature.com/articles/s41598-023-44689-0

2. **"Computer-aided classification of fetal images from ultrasound data"**
   - URL: https://link.springer.com/article/10.1007/s00330-007-0604-3

3. **"Segmentation of ultrasound images using deep learning"**
   - URL: https://ieeexplore.ieee.org/abstract/document/7065897

### Model Architecture

The project utilizes a pre-trained deep learning model (stored in `.pkl` format) that has been specifically trained for fetal organ classification. The model architecture is based on transfer learning techniques, which allows for accurate classification even with limited training data. The model has been trained on a diverse dataset of fetal ultrasound images, ensuring robust performance across different imaging conditions and fetal positions.

## Features

- Upload fetal ultrasound images
- Real-time classification of fetal organs
- Support for multiple organ categories:
  - Fetal brain
  - Fetal thorax
  - Fetal abdomen
  - Fetal femur
- Modern and responsive user interface
- Drag and drop file upload
- Real-time prediction confidence scores

## Technologies Used

- Python
- Flask
- TensorFlow/Keras
- HTML5/CSS3
- JavaScript
- Deep Learning (Transfer Learning)

## Setup and Installation

1. Clone the repository:
```bash
git clone https://github.com/malakazlan/FetalOrganDetetction-lassification.git
cd FetalOrganDetetction-lassification
```

2. Create a virtual environment and activate it:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install the required packages:
```bash
pip install -r requirements.txt
```

4. Run the application:
```bash
python app.py
```

5. Open your browser and navigate to `http://localhost:5000`

## Project Structure

```
├── app.py              # Main Flask application
├── model/             # Directory containing the trained model
│   └── model.pkl      # Pre-trained model for fetal organ classification
├── static/            # Static files (CSS, uploads)
│   ├── styles.css     # Custom styles
│   └── uploads/       # Uploaded images directory
├── templates/         # HTML templates
│   └── index.html     # Main page template
└── requirements.txt   # Project dependencies
```

## Usage

1. Open the web application in your browser
2. Click the upload area or drag and drop an ultrasound image
3. Wait for the prediction results
4. View the identified organ and confidence score

## Research Impact

This project contributes to the field of medical imaging by:
- Providing an accessible tool for healthcare providers to classify fetal organs
- Implementing state-of-the-art deep learning techniques for medical image analysis
- Supporting early detection and monitoring of fetal development
- Offering a user-friendly interface for medical professionals

## Future Work

- Integration with medical imaging systems
- Support for additional organ classifications
- Real-time video analysis capabilities
- Enhanced accuracy through continuous model training
- Integration with electronic health records (EHR) systems

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Author

Malak Azlan 