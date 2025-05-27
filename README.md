# GourmetGlimpse 🍳

GourmetGlimpse is a sophisticated **Food Image to Recipe Converter** specifically tailored for Indian cuisine. By leveraging deep learning, it analyzes food images and retrieves the most relevant recipes from a comprehensive dataset.

## ✨ Features

- **Image Recognition**: Uses a pre-trained DenseNet201 model to identify food items from uploaded images or camera captures.
- **Accurate Recipe Retrieval**: Matches image features against a pre-computed database of over 1000 Indian recipes.
- **Comprehensive Details**: Provides calorie counts, cooking times, ingredients, and step-by-step directions for each identified dish.
- **Modern UI**: A clean, responsive web interface built with Django and modern CSS.

## 🚀 Getting Started

### Prerequisites

- Python 3.10+
- Django 5.x
- TensorFlow / Keras
- NumPy / SciPy

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Kronodile/GourmetGlimpse.git
   ```
2. Set up a virtual environment:
   ```bash
   python -m venv venv
   source venv/Scripts/activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Running the App

Start the Django development server:
```bash
python src/manage.py runserver
```
Visit `http://127.0.0.1:8000/` in your browser.

## 🛠️ Technology Stack

- **Backend**: Django (Python)
- **Deep Learning**: TensorFlow, Keras (DenseNet201)
- **Frontend**: HTML5, Vanilla CSS
- **Data Storage**: SQLite3, JSON, Pickle (for encodings)

## 👤 Author

- **Kronodile** ([@pranavreddy27](https://github.com/pranavreddy27.m@gmail.com))

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
