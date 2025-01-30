# BloomClassify

BloomClassify is a simple web application that predicts the class of a flower based on its petal and sepal measurements. It is built using Flask and a machine learning model trained on the Iris dataset.

## Features
- Predicts flower species based on sepal and petal dimensions.
- Built with Flask for an easy-to-use web interface.
- Uses a pre-trained machine learning model.
- Simple and lightweight application.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ad1lhasan/BloomClassify.git
   cd BloomClassify
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Flask application:
   ```bash
   python 1.py
   ```

4. Open your browser and navigate to:
   ```
   http://127.0.0.1:5000/
   ```

## Usage
1. Enter the sepal length, sepal width, petal length, and petal width in the web interface.
2. Click the **Predict** button.
3. The application will display the predicted flower class.

## Files
- `1.py` - Main Flask application.
- `model.pkl` - Pre-trained machine learning model.
- `iris_data.ipynb` - Jupyter Notebook used for training the model.
- `templates/index.html` - HTML template for the web interface.
- `requirements.txt` - List of dependencies.

## License
This project is licensed under the MIT License. See `LICENSE` for details.

---


