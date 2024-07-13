# Human Disease Prediction

## Overview
This project aims to predict human diseases based on user-provided symptoms using various machine learning algorithms. The system supports predictions using Decision Tree, Naive Bayes, K-Nearest Neighbors (KNN), and Random Forest models. Additionally, a user-friendly interface created with Tkinter allows users to select up to 5 symptoms to receive a disease prediction.

## Key Features
- **Multiple Prediction Models:** Implements four different machine learning algorithms (Decision Tree, Naive Bayes, KNN, Random Forest) to provide robust and accurate disease predictions.
- **User Interface:** Developed using Tkinter, the UI enables users to easily select symptoms and receive disease predictions.
- **Symptom Selection:** Users can choose up to 5 symptoms from a predefined list to get a diagnosis.

## Project Structure
- **model_training:** Contains scripts for training the machine learning models.
- **ui:** Contains the Tkinter-based user interface scripts.
- **data:** Includes the dataset used for training and testing the models.
- **notebooks:** Jupyter notebooks for exploratory data analysis and model evaluation.

## Installation

### Prerequisites
Ensure you have Python 3.x installed on your system. You can download it from [python.org](https://www.python.org/).

### Clone the Repository
```bash
git clone https://github.com/farihashk/humandiseaseprediction.git
cd humandiseaseprediction
```

### Create a Virtual Environment
It's recommended to use a virtual environment to manage dependencies.
```bash
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

### Install Dependencies
Install the required Python packages using the `requirements.txt` file.
```bash
pip install -r requirements.txt
```

## Usage

### Train the Models
run mpl.ipynb in Jupyter Notebook or Google Colab

### Launch the User Interface
On running mpl.ipynb, the application window will open, allowing you to select symptoms and receive disease predictions.

### Prediction Example
1. Launch the application.
2. Select up to 5 symptoms from the dropdown menus.
3. Click the "Predict" button.
4. View the predicted disease in the result section.

## Contributing
We welcome contributions to this project. If you have suggestions, bug reports, or feature requests, please open an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact
For any questions or inquiries, please contact fariha.shaikh02@gmail.com
