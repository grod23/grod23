# 👋 Hi, I'm Gabriel Rodriguez

🎓 **Computer Science Student | Machine Learning Researcher | Computer Vision Enthusiast**

Welcome to my GitHub! I'm currently pursuing a B.S. in Computer Science with a Minor in Data Science at California State University, Fullerton. My passion lies in building intelligent systems that solve real world problems using machine learning, deep learning, and computer vision.

## 🚀 Projects

### 📝 **doPlan Dataset for Long-Horizon Autonomous Driving**

Contributed to the development of **doPlan**, a newly introduced autonomous driving dataset created by the **[Mi3 Lab at UC Merced](https://mi3-lab.github.io/)** for studying how autonomous vehicles interpret and execute natural language instructions.

Supported dataset development through **manual annotation of 1,000+ driving instructions**, helping create passenger-oriented language annotations grounded in real-world driving scenarios. Unlike traditional navigation commands, doPlan focuses on instructions similar to how a passenger would communicate with a human driver, including both **short- and long-horizon instructions across temporally diverse driving segments**.

**Contributions:**
- Annotated and verified 1,000+ natural language driving instructions
- Supported annotation quality control and dataset refinement
- Helped prepare multimodal training and evaluation data for autonomous driving research

**Research applications:**
- **Natural passenger interaction:** Enables research into autonomous vehicles that understand conversational, human-like instructions similar to those given to a taxi driver.
- **Emergency response and external coordination:** Enables exploration of how autonomous vehicles can interpret instructions from external actors such as first responders in dynamic environments.
- **Instruction composition:** Supports research on combining multiple goals and instructions into coherent long-horizon driving plans.

### 👁️ **Computer Vision for Early Screening of Eye and Brain Disease**
   
  Developed a **U-Net-based deep learning model** for retinal vessel segmentation to analyze **Spontaneous Venous Pulsations (SVP)** A clinically relevant biomarker for **glaucoma** and **elevated intracranial pressure (ICP)**.  

  Implemented **image preprocessing techniques** including **green channel extraction** and **CLAHE** to enhance vessel contrast. Designed a pipeline to compare vessel diameter across temporal frames, enabling **quantitative pulsation analysis** for early disease screening.  

  🏆 *Presented at the CSU Student Research Competition (Engineering & Computer Science), representing Cal State Fullerton.*

### 🎗️ **Breast Cancer T-Stage Classifier (Multimodal 2.5D CNN)**
  
  This project presents a **multimodal** approach to breast cancer T-stage classification, integrating structured clinical data, radiomic features, and 3D breast MRI (DICOM) volumes within a unified framework. I **co-authored a research paper** and **led a team of three students**, overseeing model design, experimentation, and evaluation.
  MRI volumes were processed using a **MONAI-based medical imaging pipeline**, incorporating **region-of-interest selection**, **spatial resampling**, and **intensity normalization** to ensure consistency across           patients and imaging protocols. For modeling, we employed a **late-fusion 2.5D convolutional neural network** with a **ResNet backbone**, stacking neighboring slices to capture volumetric context while preserving the    efficiency of 2D convolutions. Uitilization of the 2.5D CNN exhibited strong late stage tumor analysis enhancing **T-stage 3 recall to 87%** while achieving a **97% F1-score on T-stage 4 tumors**. 

  **📄 Paper:**  
  *Breast Cancer T-Stage Prediction and Classification Using Machine Learning* —  
  Gabriel Rodriguez · Sara Lee · Sunny Palaco  
  👉 [Read on GitHub](https://github.com/grod23/Breast-Cancer-Stage-Prediction/blob/main/BreastMRIPaper.pdf)


### 🧠 **MRI Brain Tumor Classifier**
  
  A **convolutional neural network (CNN)** built with **PyTorch** and **OpenCV** to classify glioma, meningioma, and pituitary tumors from MRI scans. Attained **89% accuracy** and **90% recall** across tumor-positive     cases. Leveraged **Explainable AI (XAI)** methods such as **Grad-CAM** for model inteprebaility and clinical trust.

## 🧰 Technical Toolbox

**Languages**: Python, SQL

**Libraries**: PyTorch, Torchvision, OpenCV, MONAI, NumPy, Pandas, Scikit-learn, Matplotlib

**Concepts**: Machine Learning, Deep Learning, Computer Vision, Segmentation, Data Preprocessing, Agile Methodologies

**Tools**: CUDA, Git/GitHub, PyCharm, Visual Studio, JupyterLab, Google Colab

## 🌱 What I'm Working On

- 🚗 **Driving Intent Decomposition for Autonomous Driving (UC Merced Research Fellowship)**

Developing methods for improving **long-horizon instruction understanding in Vision-Language-Action (VLA) models** for autonomous driving.

This research builds on the instruction-following challenges addressed by **doPlan**, investigating whether complex driving instructions can be decomposed into temporally grounded sub-instructions and recomposed while preserving the original **driving intent**. The project explores instruction decomposition/composition, trajectory-based evaluation, and multimodal reasoning for autonomous systems.

**Research Focus:**
- Vision-Language-Action (VLA) models
- Natural language instruction grounding
- Autonomous driving scene understanding
- Trajectory-based evaluation of driving intent

## 📫 Let's Connect

- 📍 Location: Fullerton, CA  
- 🔗 [LinkedIn](https://www.linkedin.com/in/gabrielrodriguezml2003)  
- 💼 [Resume](https://github.com/grod23/Gabriel-Rodriguez-Resume.git)
- ✉️ Email: gabe7rodriguez@gmail.com

---

Thanks for stopping by! Feel free to explore my repositories, contribute, or reach out if you're working on something exciting in ML, AI, or data science.
