# plant-leaf-disease
# 🌿 Plant Leaf Infection Detection using Image Processing and Classical Feature-Based Techniques

## 🔍 Overview
This project is designed to detect and quantify plant leaf infections using **classical image processing techniques** combined with automated CLI-based results. The system processes each input leaf image, identifies infected regions, calculates infection spread as a percentage, and displays detailed image processing steps.

It is ideal for early detection of crop disease, especially for agricultural stakeholders like **farmers**, **researchers**, and **agri-tech developers**.

---

## 🛠 Tools & Technologies Used
- **Python**
- **OpenCV** – Image processing and analysis
- **NumPy** – Mathematical operations
- **Matplotlib** – Visualizations
- **Command Line Interface (CLI)** – Automated user interaction
- **PlantVillage Dataset** – Real-world leaf image dataset

---

## 🧠 Methodology

### 1. 📥 Image Acquisition
- Accepts images from the **PlantVillage** dataset or local folders.
- Command-line prompts to confirm and process all images in a given folder.

### 2. ⚙️ Image Preprocessing
- Conversion to grayscale
- Blurring to reduce noise
- Color space conversion (e.g., **HLS**, **masking**, **ROI**)
- Mean shift filtering
- Canny edge detection
- Contour detection to define leaf shape and infected region

### 3. 📊 Infection Calculation
- Calculates key metrics per image:
  - **Total Leaf Area**
  - **Infected Area**
  - **Percentage of Infection Spread**
  - 
### 4.📊 Disease Analysis and Infection Calculation
Calculated:
Total Leaf Area
Infected Area
Percentage of Infection

### 5. 💡 Future Improvements
Deploy as a web/mobile app for farmers

Add multilingual voice-based guidance

Integrate with drone-captured images for large field assessments

Include pest detection alongside disease
#### 📌 Sample Output:

<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/184ec609-8c55-406e-b9e9-b45cc212a354" />
<img width="914" height="513" alt="image" src="https://github.com/user-attachments/assets/e2a36ee8-da66-42ca-b1a1-38aeb52788c9" />
<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/c94a2549-70c1-4fea-a852-e543cc0d076e" />


Perimeter: 1547.65
Total Area: 167.00
Infected Area: 51.00
Percentage of Infection Region: 30.54%
