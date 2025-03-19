
# **A5 Project: Modification on Conventional Visible and Infrared Image Fusion Methods for Real-Time Applications**

## **Overview**  
This project explores the fusion of visible and infrared images using various color spaces (**YCbCr, LAB, LCH**) and the **Laplacian Pyramid (LP) fusion method**. The primary goal is to enhance the quality and efficiency of fused images for **real-time applications** such as **surveillance, medical imaging, and remote sensing**.

## **Features**  
- **Image Fusion with Different Color Spaces**: YCbCr, LAB, and LCH color spaces.  
- **Laplacian Pyramid (LP) Fusion Method**: Used to merge visible and infrared images.  
- **Performance Evaluation**: Metrics such as **PSNR, SSIM, and entropy** analyzed.  
- **Computational Time Analysis**: Processing time recorded for **CUDA vs. CPU** implementations.  
- **Optimization for Real-Time Processing**: Algorithm fine-tuning and hardware acceleration strategies explored.  

---

## **Installation**  
### **Prerequisites**  
Ensure the following dependencies are installed:  
- Python 3.x  
- OpenCV  
- NumPy  
- Matplotlib  
- PyTorch (if using CUDA acceleration)  

### **Setup**  
Clone the repository:  
```bash
git clone https://github.com/MOMOZ69/A5_Project_Files.git
cd A5_Project_Files
```
Install required dependencies:  
```bash
pip install -r requirements.txt
```

---

## **Usage**  
Run the main script for image fusion:  
```bash
python main.py --input1 visible_image.jpg --input2 infrared_image.jpg --method LP --color_space YCbCr
```
Options:  
- `--method` → Fusion method (default: LP)  
- `--color_space` → Choose from `YCbCr`, `LAB`, `LCH`  

For CUDA acceleration:  
```bash
python main.py --use_cuda
```

---

## **Results and Evaluation**  
- **Performance Metrics**: PSNR, SSIM, and entropy are calculated for each fused image.  
- **Timing Analysis**: Processing times for CPU and CUDA implementations are recorded and compared.  
- **Optimization Techniques**: Parameter fine-tuning and hardware acceleration strategies tested.  

---

## **Contributing**  
Feel free to contribute by opening issues or submitting pull requests.  

---

## **License**  
This project is licensed under the **MIT License**.  
