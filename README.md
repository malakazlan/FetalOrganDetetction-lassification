# Fetal Organ Detection Classification

A web application that uses deep learning to classify fetal ultrasound images into different organ categories.

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

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Author

Malak Azlan 