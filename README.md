# YOLOv8 Ship Charger Detection

This project fine-tunes **YOLOv8** to detect and localize **ship charging stations** (labeled as “boat”) to help electric ships autonomously find and dock with chargers safely.

### 🧠 Model
- Base model: `yolov8l.pt`
- Framework: PyTorch + Ultralytics YOLOv8
- Trained on a custom dataset of ship-charger images in Google Colab (Tesla T4 GPU)
- 10 epochs, mAP@50 ≈ 0.95, mAP@50-95 ≈ 0.89

### 📄 Contents
- `YOLOv8_DeepSORT_Training.ipynb` – full training notebook  
- `fixed_data.yaml` – dataset configuration  
- `samples/` – example results and predictions  
- `README.md` – this file

### 🎥 Demo
Result video available in Drive: `final_test4_result.mp4`
