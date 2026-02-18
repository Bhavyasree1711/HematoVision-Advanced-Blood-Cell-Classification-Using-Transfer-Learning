# 5. Project Development Phase

## Development Process
- **Model Development:** Used Jupyter Notebook to fine-tune MobileNetV2 on the Kaggle "Blood Cell Images" dataset (12,000 images).
- **Backend:** Flask app for handling uploads, inference, and serving results.
- **Frontend:** HTML templates for home and result pages.
- **Integration:** Connected model to backend for real-time classification.

## Code Structure
- `app.py`: Main Flask application.
- `BloodCellClassifier.ipynb`: Model training script.
- `BloodCell.h5`: Trained model.
- `home.html`, `result.html`: Frontend templates.

## Performance Testing

### Model Performance Metrics
- **Accuracy:** 96% on test set.
- **Precision/Recall:** High for all classes.
- **Confusion Matrix:** Minimal misclassifications.

### System Performance
- **Response Time:** <2 seconds per image.
- **Throughput:** Handles 10 concurrent requests.
- **Resource Usage:** Low CPU/GPU during inference.

### Testing Results
- Passed all performance benchmarks.
- Optimized model for efficiency.

## User Acceptance Testing (UAT)

### Test Cases
1. Upload valid image → Correct classification.
2. Upload invalid image → Error message.
3. Multiple users → No conflicts.
4. Educational mode → Feedback provided.

### UAT Results
- All test cases passed.
- Users (simulated pathologists/students) satisfied with accuracy and usability.
- Feedback: Intuitive interface, fast results.

### Issues and Resolutions
- Minor UI bugs fixed.
- Model retrained for edge cases.