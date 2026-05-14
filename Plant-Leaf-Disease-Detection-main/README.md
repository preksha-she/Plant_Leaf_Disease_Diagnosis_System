# Plant Disease Detection System

This project is a comprehensive plant disease detection system using machine learning and computer vision techniques. It includes various models and tools for analyzing plant health, detecting diseases, and providing insights through visualizations.

## Features

- Disease prediction using CNN models
- Leaf health analysis
- Multi-leaf analyzer
- YOLO object detection
- Metrics visualization
- Chatbot for disease information
- Jupyter notebooks for training and testing

## Installation

1. Clone the repository:
   ```
   git clone <your-repo-url>
   cd plant-disease-detection
   ```

2. Create a virtual environment:
   ```
   python -m venv .venv
   source .venv/bin/activate  # On Windows: .venv\Scripts\activate
   ```

3. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage

### Running the Application
```
python app.py
```

### Training Models
Use the Jupyter notebooks:
- `Train_plant_disease.ipynb` for training the main model
- `plant-diseases-detection-cnn-97-acc.ipynb` for CNN training

### Testing
- `test_predictor.py` for testing predictions
- `Test_Plant_Disease.ipynb` for notebook-based testing

## Models

- `trained_model.h5`: Main trained model
- `updated_model.h5`: Updated version
- `updated_plant_model.h5`: Latest plant model
- `yolov8n.pt`: YOLOv8 model for detection

## Project Structure

- `app.py`: Main Flask application
- `disease_predictor.py`: Core prediction logic
- `leaf_health_analyzer.py`: Leaf analysis tools
- `multi_leaf_analyzer.py`: Multi-leaf processing
- `yolo_detector.py`: YOLO detection implementation
- `METRICS_VISUALIZATION.py`: Performance metrics
- `disease_chatbot.py`: Chatbot functionality

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.
