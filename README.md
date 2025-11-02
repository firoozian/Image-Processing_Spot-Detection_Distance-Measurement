## 🔬 Bright Spot Detection & Distance Measurement Tool

This project allows users to **detect bright points** in grayscale microscopy images (e.g., TEM/STEM), **select pairs of points manually**, and **measure the distances** between them interactively.

### 🧩 Features
- Applies **Gaussian Blur** and **Laplacian filtering** to enhance bright spots  
- Detects bright points and marks them with green circles  
- Allows **manual point selection** by mouse click  
- Calculates **horizontal, vertical, and actual (Euclidean) distances** between two selected points  
- Displays all distances on a **white side panel** for easy reading  
- Saves the final annotated image automatically  

### ⚙️ Requirements
Make sure you have the following installed:
```bash
pip install opencv-python numpy matplotlib
```

### 📁 Usage
1. Place your grayscale image in the same directory as the script.  
2. Update the script with your image path:
   ```python
   image = cv2.imread('your_image_name.jpg', cv2.IMREAD_GRAYSCALE)
   ```
3. Run the script:
   ```bash
   python main.py
   ```
4. A window will open:
   - **Left-click** on two detected points → distance will be displayed on the side box.  
   - Continue selecting new pairs to measure more distances.  
5. Press any key to exit.  
6. The annotated image will be saved as `final_image.jpg`.

### 📏 Notes
- All distances are calculated **in pixels by default**.  


### 🖼 Example Output
Detected bright spots and measured distances will be displayed as:
- Green circles → detected points  
- Blue lines → measured distances  
- Red numbers → line indices  
- Distance values → shown on white sidebar  

### 💾 Output File
`final_image.jpg`  
contains the final annotated image with all drawn measurements.

### 🧠 Author
Sina Firoozian 
Sina.firuzian@gmail.com

