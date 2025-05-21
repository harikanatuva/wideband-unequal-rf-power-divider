# Wideband Unequal RF Power Divider

This project presents a wideband unequal power divider with enhanced power dividing ratio, fully matching bandwidth, and filtering performance. Based on the IEEE paper titled:

**“Wideband Unequal Power Divider With Enhanced Power Dividing Ratio, Fully Matching Bandwidth, and Filtering Performance”**  
*(IEEE Transactions on Microwave Theory and Techniques, VOL. 70, NO. 6, June 2022)*

## 📚 Overview

- 📡 Designed for use in microwave communication systems, radar, and signal distribution.
- 🌀 Uses a **leading triple-mode resonator** to improve return loss, isolation, and bandwidth.
- 📈 Achieves power dividing ratios like **4:1 and 8:1** with **>95% bandwidth**.
- 🔧 Implemented and simulated in **HFSS and ADS**.

## 🎯 Objectives

- Improve upon Wilkinson Power Divider limitations
- Achieve enhanced:
  - Return Loss (|S11| < -10 dB)
  - Isolation (|S32| < -14 dB)
  - Insertion Loss balance between output ports

## 🧪 Results


| Parameter              | Simulated Result            | Measured Result              |
|------------------------|----------------------------|-----------------------------|
| Return Loss (&#124;S11&#124;)    | 1.25–3.54 GHz (95.4%)       | 1.27–3.57 GHz (95.8%)       |
| Insertion Loss &#124;S21&#124;   | -1.04 to -1.35 dB           | -1.38 to -1.85 dB           |
| Insertion Loss &#124;S31&#124;   | -6.91 to -7.23 dB           | -7.08 to -7.67 dB           |
| Isolation (&#124;S32&#124;)      | Better than -13 dB          | Better than -14 dB (100%)   |
| Matching Bandwidth     | Full 95.8% for &#124;S11&#124;, &#124;S22&#124;, &#124;S33&#124; |                             |
	


## 📁 Files Included

- `Wideband_Unequal_RF_Power_Divider_IEEE_Summary.pdf`: Summary of the IEEE paper with key performance results
- `images/`: Folder for simulation diagrams or design schematics (HFSS/ADS)
- `simulations/`: Optional folder for raw simulation files (if sharing)

## 👨‍🔬 Contributors

- Harshitha N   
- Pujith B  
- Devika Vinod  
- Hasini  

Under the course: **RF & Simulation Lab – 19ECE381**

## 📰 Reference

Wang, D., Guo, X., & Wu, W. (2022).  
*Wideband Unequal Power Divider With Enhanced Power Dividing Ratio, Fully Matching Bandwidth, and Filtering Performance*.  
IEEE Transactions on Microwave Theory and Techniques, Vol. 70, No. 6.
