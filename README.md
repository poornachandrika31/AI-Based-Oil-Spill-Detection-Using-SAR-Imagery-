# 🌊 AI SpillGuard — Oil Spill Detection using Deep Learning

AI SpillGuard is an AI-powered environmental monitoring system that detects and segments oil spills from SAR (Synthetic Aperture Radar) satellite imagery using a U-Net deep learning model.

The application provides:
- Real-time oil spill detection
- Semantic segmentation masks
- Spill severity analysis
- Probability heatmaps
- Visual analytics dashboard
- PDF report generation
- Historical prediction tracking using MongoDB

---

# 🚀 Features

✅ Deep Learning-based Oil Spill Segmentation  
✅ U-Net Semantic Segmentation Architecture  
✅ Streamlit Interactive Dashboard  
✅ SAR Image Analysis  
✅ Spill Boundary Detection  
✅ Probability Heatmaps & Analytics  
✅ PDF Report Generation  
✅ MongoDB Integration for Prediction History  
✅ Real-time Visualization  

---

# 🧠 Model Architecture

The project uses a U-Net convolutional neural network trained for semantic segmentation on SAR satellite imagery.

### Pipeline

1. Upload SAR Image
2. Image Preprocessing
3. U-Net Inference
4. Probability Map Generation
5. Binary Mask Creation
6. Spill Severity Analysis
7. Report Generation

---

# 🛰️ What is SAR Imagery?

Synthetic Aperture Radar (SAR) imagery enables all-weather, day-and-night monitoring of ocean surfaces.

Oil spills appear as darker regions in SAR images because oil dampens ocean surface waves, reducing radar backscatter.

---

# 📊 Outputs

The system generates:

- Oil segmentation masks
- Spill overlays
- Spill boundaries
- Coverage analytics
- Confidence scores
- Historical trend analysis

---

# 🖼️ Sample Results

## Original Image
![Input](sample_images/sample_input.png)

## Segmentation Output
![Output](sample_images/sample_output.png)

## Overlay Result
![Overlay](sample_images/overlay_result.png)

---

# 🛠️ Tech Stack

## AI / Deep Learning
- TensorFlow
- Keras
- U-Net Architecture

## Computer Vision
- OpenCV
- NumPy

## Frontend
- Streamlit

## Database
- MongoDB

## Visualization
- Matplotlib
- Pandas

## Report Generation
- ReportLab

---

# 📦 Installation

## Clone Repository

```bash
git clone https://github.com/yourusername/oil-spill-detection-ai.git
cd oil-spill-detection-ai
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

## Run Application

```bash
streamlit run app.py
```

---

# 📁 Project Structure

```bash
oil-spill-detection-ai/
│
├── app.py
├── requirements.txt
├── README.md
├── model/
├── notebooks/
├── sample_images/
└── assets/
```

---

# 📈 Future Improvements

- Real-time satellite feed integration
- Multi-class marine pollution detection
- Cloud deployment
- Mobile-compatible dashboard
- Temporal spill tracking
- Geospatial mapping integration

---

# 👩‍💻 Author

Developed by Chandrika  
AI & Computer Vision Enthusiast

---

# 📜 License

This project is licensed under the MIT License.
