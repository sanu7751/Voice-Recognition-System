Overview
  
  This project is a machine learning-based speaker recognition system that identifies the speaker from an uploaded audio file. It uses various classification      models to achieve high accuracy in recognizing speaker attributes like name, age, etc.

Features
  Upload an audio file (WAV format)
  Process and extract features from the audio
  Use machine learning models (Random Forest, SVM, KNN) for speaker classification
  Display the predicted speaker information on a web interface

Technologies Used
  Python (Flask, scikit-learn, librosa, numpy, pandas)
  HTML, CSS, JavaScript (Frontend UI)
  Machine Learning (Random Forest, SVM, KNN)
  Model Serialization (joblib)

Installation

    Prerequisites
      Ensure you have Python installed on your system. Install dependencies using:
    
    Running the Project
      Train the model by running:
      Start the Flask server:
      Open a browser and go to:

Project Structure

    API Endpoints
      GET / - Home page
      POST /predict - Upload an audio file and get the predicted speaker
    
    Troubleshooting
      Ensure all dependencies are installed.
      Verify that index.html is inside the templates/ directory.
      If ModuleNotFoundError: No module named 'sklearn' occurs, run pip install scikit-learn.
    
    Contributing
      Feel free to contribute by creating issues or pull requests.
    
    License
      This project is licensed under the MIT License.
