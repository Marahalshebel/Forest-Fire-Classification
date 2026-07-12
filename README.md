# Forest Fire Classification

## Overview
This project demonstrates an image classification model developed using Google Teachable Machine.
The model classifies forest images into three classes:
- Fire
- Smoke
- No Fire
The trained model was exported in TensorFlow (Keras) format and used in Python to predict the class of an input image.

## Project Files
```
Forest-Fire-Classification/
│
├── Task01_Forest_Fire_Classification.ipynb
├── keras_model.h5
├── labels.txt
├── screenshot.png
└── README.md
```

| File | Description |
|------|-------------|
| `Task01_Forest_Fire_Classification.ipynb` | Python notebook for loading the model and making predictions |
| `keras_model.h5` | Trained image classification model |
| `labels.txt` | Class labels |
| `screenshot.png` | Screenshot showing the prediction result |

---
## How to Run
1. Open the notebook in Google Colab.
2. Upload the following files:
   - `keras_model.h5`
   - `labels.txt`
   - A test image
3. Run all cells.
4. The notebook will display the predicted class and confidence score.

---
## Model Evaluation
The model was evaluated using several test images that were not used during training.
The model correctly classified most images into the three classes:
- Fire
- Smoke
- No Fire

Some images with colors similar to fire, such as sunsets, were occasionally classified as Fire. This indicates that the model could be further improved by using a more diverse training dataset.

---
## Example Output

```
Predicted Class: Fire
Confidence Score: 98.5%
```

Replace this section with the screenshot of your output.

---

## Project Workflow

1. Train an image classification model using Google Teachable Machine.
2. Export the trained model in TensorFlow (Keras) format.
3. Load the model in Python.
4. Read an input image.
5. Predict the image class and display the confidence score.
6. 
---
## Future Improvements
Possible improvements include:
- Increase the number of training images.
- Add more challenging "No Fire" examples such as sunsets and orange skies.
- Improve dataset diversity.
- Train the model using a larger dataset for higher accuracy.
