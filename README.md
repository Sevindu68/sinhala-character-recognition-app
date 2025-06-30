# Sinhala Letter Recognition App

This project is a Sinhala letter recognition application. It uses a K-Nearest Neighbors (KNN) algorithm for model training and provides a Tkinter-based UI for drawing and predicting Sinhala letters.

## Features

- **KNN Model**: Trained to recognize Sinhala letters.
- **Tkinter UI**: Draw letters directly in the app.
- **Prediction**: Instantly predicts the drawn letter.

## How It Works

1. **Draw**: Use the drawing canvas to draw a Sinhala character with your mouse.
2. **Save**: Click the green "SAVE" button to save your drawing.
3. **Predict**: Click the blue "PREDICT" button to analyze your drawing and get the predicted character.
4. **Clear**: Use the yellow "CLEAR" button to erase the canvas and start over.
5. **Exit**: Click the red "exit" button to close the application.

## Requirements

- Python 3.x
- `scikit-learn`
- `tkinter`
- `numpy`
- `Pillow`

## Usage

1. Clone this repository.
2. Install dependencies:
    ```bash
    pip install scikit-learn numpy pillow
    ```
3. Run the application:
    ```bash
    python app.py
    ```

## Project Structure

- `sinhala-character-recognition.ipynb` - Main Tkinter application with UI and prediction logic.
- `sinhala-character-knn.sav` - Trained KNN model file.
- `sinhala_letter_recognition.py` - Additional Python script for model training and experimentation.
- `icon.png` - Application icon.
- `images/` - Directory for storing image assets (currently empty).
- `data set` - Data Set which is used to train the model
- `README.md` - Project documentation.

## License

This project is licensed under the MIT License.
