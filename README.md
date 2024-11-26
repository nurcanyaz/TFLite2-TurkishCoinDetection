# TFLite2-TurkishCoinDetection  



**TFLite2-TurkishCoinDetection** is an AI model designed to detect and classify Turkish Lira coins using TensorFlow Lite. The model is lightweight and optimized for deployment on resource-constrained devices such as mobile and IoT systems.  

## Features  
- **Turkish Lira Coin Detection**: Accurately classifies coins like 1 TL and 50 kuruş.  
- **TensorFlow Lite Support**: Optimized for mobile and embedded systems.  
- **Simplified Training Workflow**: Supports data labeling using tools like LabelImg and Roboflow.  

## Technical Details  
- **Model**: SSD Mobilenet V2 FPNLite 320x320  
- **Training**: Built using TensorFlow Object Detection API and converted to TFLite format.  
- **Performance**:  
  - **Accuracy**: Over 90%  
  - **mAP (mean Average Precision)**: 85%  

## Use Cases  
- Mobile applications to assist visually impaired individuals in recognizing coins.  
- Real-time object detection systems for Turkish coins.  

## Installation and Usage  

### Requirements  
- Python 3.7+  
- TensorFlow  
- OpenCV
 
### Train the Model
Run the coin_model.ipynb file in Jupyter Notebook to start the training process.

# Example Usage
Integrate the trained model into a mobile application to perform coin recognition using live camera feeds.

# Future Work
- Enhance model performance with a more extensive and diverse dataset.
- Optimize for real-time recognition capabilities.
- Expand the model to recognize coins from different countries.


See you next project:)
