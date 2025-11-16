# Assignment11

This project performs image classification on a small dataset consisting of five categories: sunflower, dalmatian, dollar_bill, pizza, and soccer_ball.

## Steps Completed
- Loaded image dataset from folder structure
- Resized all images to 64x64
- Flattened image data for model input
- Split data into training and testing sets
- Trained a Random Forest classifier using GridSearchCV
- Evaluated the model using accuracy, classification report, and confusion matrix
- Saved the best model using joblib

## How to Run
1. Upload `images.zip` to Google Colab.
2. Unzip the folder using:
   `!unzip /content/images.zip -d /content/`
3. Run the notebook cells from top to bottom.
4. The trained model will be saved as `rf_image_model.pkl`.

## Requirements
- scikit-learn
- numpy
- matplotlib
- scikit-image
- joblib
