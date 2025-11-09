# Automatic Number Plate Detection and Recognition using YOLOv8 + EasyOCRnumber-plate-detection:

📘 Project Overview:
. This project focuses on Automatic Number Plate Detection and Recognition using the YOLOv8 object detection model combined with EasyOCR for text extraction
. It can detect vehicle number plates from uploaded images or real-time webcam feeds and extract the plate numbers as readable text
. Built with a focus on real-world robustness, handling nvironmental conditions such as varying lighting (day/night), weather effects

📂 Project Structure:
 vehicle_project/
├── app.py                    
├── requirements.txt           
├── runs/
│   └── detect/
│       └── train/
│           └── weights/
│               └── best.pt    

🧠 Technical Tags:
  * YOLOv8
  * EasyOCR
  * OpenCV
  * PyTorch
  * Streamlit

Libraries:
 * NumPy
 * Pandas
 * Matplotlib
 * Albumentations
 * Pillow - {image handling}

💡 Purpose of Streamlit:
- Upload images for number plate detection
- See extracted text from EasyOCR
- Use their webcam for real-time detection

⚙️ Streamlit Workflow Summary:

  User uploads image or starts webcam
      ↓
  YOLOv8 detects plate region
      ↓
  EasyOCR reads text from detected plate
      ↓
  Streamlit displays bounding boxes + recognized text
      ↓
  Performance metrics shown
      ↓
  Option to download results (CSV)

 Conclusion:
      This project successfully deduct automated vehicle number plate detection and recognition system using YOLOv8 for object detection and EasyOCR for text extraction and Through systematic data collection, preprocessing, model training, and deployment.

      It will be foundation for:
         ! traffic monitoring
         ! toll collection
         ! parking management

