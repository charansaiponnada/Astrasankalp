# 🚀 AstraSankalp

_Astra_ 🌌 – Spirit of the Stars  
_Sankalp_ 🔭 – Unwavering Determination  

**AstraSankalp** blends celestial vision with grounded execution. We are a passionate team exploring the frontiers of **AI**, **space science**, and **geospatial intelligence**—where innovation orbits ambition.

---

## 🛰️ Project: Lunar Terrain Hazard Detection  
**Hackathon:** ISRO Bharatiya Antariksh Hackathon 2025  
**Problem Statement:** PS11 – Novel Method to Detect Landslides & Boulders on the Moon

> This project focuses on building a robust AI pipeline that uses Chandrayaan satellite imagery to identify hazardous **boulders**, segment **landslides**, and estimate their **origin points**—enhancing future lunar rover navigation safety.

---

## 🌕 Mission Goals

- 🔍 Detect small **boulders** via classical filters + deep learning
- 🌐 Segment **landslides** using semantic segmentation models (U-Net / DeepLabV3+)
- 📍 Identify **landslide origin points** with gradient tracing & DEM analysis
- 🖼️ Visualize results using interactive dashboards
- 📊 Evaluate performance with scientific metrics (IoU, precision, Euclidean distance)

---

## 🧭 Project Workflow

1. Download Chandrayaan imagery from ISSDC
2. Preprocess images (CLAHE, denoising, sharpening)
3. Detect boulders using blob filters + YOLO/CNN
4. Segment landslides using U-Net
5. Trace landslide origin points with slope analysis
6. Overlay and visualize results with Streamlit
7. Evaluate using IoU, F1-score, and distance accuracy


---

## 🧪 Technologies Used

- **Python, OpenCV, NumPy, Rasterio**
- **PyTorch / TensorFlow** for deep learning
- **YOLOv8n, U-Net / DeepLabV3+**
- **GDAL, DEM tools** for elevation analysis
- **Streamlit**, **Matplotlib** for visualization

---

## 📂 Repository Structure
```bash
AstraSankalp/
├── data/ # Chandrayaan TMC, DEM, Metadata
├── preprocessing/ # CLAHE, denoising, filters
├── boulder_detection/ # Blob filtering + CNN/YOLO
├── landslide_segmentation/
├── origin_detection/
├── visualization/ # Dashboards and overlays
├── evaluation/ # IoU, Precision, Recall
└── app/ # Final Streamlit/Flask app
```


---

## 👥 Team AstraSankalp

| Name                 | Role                          |
|----------------------|-------------------------------|
| Charan Sai Ponnada   |                               |
| Neelima vana         |                               |
| Aashvi Mourya        |                               |
| Gopal Kotha          |                               |
> Driven by the spirit of discovery and the determination to make real-world impact in space-tech, AstraSankalp is more than a team—it's a movement.

---

## 📸 Sample Results

> Coming Soon:  
> ✅ Boulder overlay visualizations  
> ✅ Landslide segmentation maps  
> ✅ Streamlit live demo link  


_"We are training AI to help ISRO rovers safely navigate the Moon by spotting rocks and landslides from satellite images.”_ 🌙
_“The Moon is not the limit—just the beginning.”_ 🌙

