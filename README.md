## 🔬 Bright Spot Detection & Distance Measurement Tool

This project allows users to **detect bright points** in grayscale microscopy images (e.g., TEM/STEM), **select pairs of points manually**, and **measure the distances** between them interactively.

### 🧩 Features
- Applies **Gaussian Blur** and **Laplacian filtering** to enhance bright spots  
- Detects bright points and marks them with green circles  
- Allows **manual point selection** by mouse click  
- Calculates **horizontal, vertical, and actual (Euclidean) distances** between two selected points  
- Displays all distances on a **white side panel** for easy reading  
- Saves the final annotated image automatically  

### 📁 Usage
 Place your grayscale image in the same directory as the script.  

 A window will open:
   - **Left-click** on two detected points → distance will be displayed on the side box.  
   - Continue selecting new pairs to measure more distances.  
 Press any key to exit.  
 The annotated image will be saved as `final_imag.jpg`.

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

