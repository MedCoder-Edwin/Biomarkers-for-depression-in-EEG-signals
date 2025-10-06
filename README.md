# Functional Connectivity Analysis of EEG Signals for Depression Biomarker Exploration

## 🧠 Motivation
Depression is one of the most prevalent psychiatric disorders worldwide, yet its diagnosis is still largely based on clinical interviews. 
Electroencephalography (EEG) provides a non-invasive window into brain activity, offering the possibility to identify objective biomarkers of depression.  
This project explores **functional connectivity metrics** applied to EEG data, aiming to uncover potential network-level alterations associated with depressive states.

---

## 📊 Data
- The dataset comprises EEG signals from three sources: an apparently healthy participant and two individuals with major depressive disorder, as provided by the project tutor.  
- Preprocessing steps include filtering, artifact rejection, and segmentation.  
- Connectivity computed across different frequency bands (e.g., delta, theta, alpha, beta and gamma).  

---

## ⚙️ Methodology
1. **Preprocessing**  
   - Band-pass and notch filtering
   - Artifact removal  
   - Segmentation into epochs  
   
2. **Functional Connectivity Analysis**  
   - Weighted Phase Lag Index (wPLI)
  
3. **Visualization**  
   - Connectivity matrices (per frequency band)    

---

## 📈 Results
- Generated connectivity matrices across multiple frequency bands.  
- Preliminary findings suggest differences in connectivity patterns that may relate to depressive states.  
- Example visualization:  
<img width="747" height="590" alt="image" src="https://github.com/user-attachments/assets/1eda52c2-1318-4150-8e8d-6d2456c2d3d5" />

  

---

## 🚀 Future Work
- Compare connectivity metrics between depressed vs. control groups.  
- Apply graph-theoretical measures (clustering coefficient, small-worldness, modularity).  
- Explore machine learning approaches for classification based on connectivity features.  
- Extend to multimodal data integration (EEG + clinical scores).  

---

## 📑 Supplementary Material
For more details on the state of the art, methodology, results, and conclusions, please see the [full Manuscript](https://github.com/MedCoder-Edwin/Biomarkers-for-depression-in-EEG-signals/blob/main/Biomarcadores%20en%20depresi%C3%B3n%20con%20se%C3%B1ales%20de%20electroencefalograf%C3%ADa%20Art%C3%ADculo%20de%20revisi%C3%B3n.pdf)
