# MATLAB Project

## Title of the Project  
**Modulation Schemes using MATLAB App Designer**

---

## Team Members
- D. Tejoprayuktha  
- R. Sneha Singh  
- Ch. Vidyadhari  
- M. Nithya Sindhuri  
- O. Ambica  

---

## Description
This project focuses on the development of a **MATLAB-based Graphical User Interface (GUI)** that provides an interactive and comprehensive platform for studying various **analog modulation techniques**.  

The GUI enables users to input essential parameters such as:
- Message amplitude  
- Message frequency  
- Carrier amplitude  
- Carrier frequency  

It then generates the corresponding:
- Message signal  
- Carrier signal  
- Modulated signal  

Additionally, it computes and displays the **modulation index**, which serves as a key performance parameter for amplitude and frequency modulation schemes.  

### Features
- Presents results in both **time domain** and **frequency domain**.  
- Allows users to observe the impact of parameter variations on both the **waveform** and its **spectral characteristics**.  
- Incorporates modulation schemes like:
  - Amplitude Modulation (**AM**)  
  - Frequency Modulation (**FM**)  
  - Double-Sideband Suppressed Carrier (**DSB-SC**)  
  - Single-Sideband Suppressed Carrier (**SSB-SC**)  
  - Vestigial Sideband (**VSB**)  
- The spectral view is obtained using **FFT** on the modulated signal.  
- By dynamically adjusting parameters such as **carrier frequency** and **modulation index**, users can visualize how these factors influence **efficiency** and **bandwidth**.  

This GUI is designed to be:
- **Intuitive and user-friendly**  
- Provides **clear graphical outputs** of the message, carrier, and modulated signals along with their spectra.  

It serves as:
- An effective **educational tool** for students learning communication systems.  
- A supportive platform for **researchers and engineers** exploring the intricacies of modulation.  

---

## Design of the App
We created the app window **“Modulation Schemes using MATLAB App Designer”** using the following components from the content library of **App Designer**:

- **Label Field**: AM, FM, DSBSC, SSBSC, VSB  
- **Buttons**: Message, Carrier, Modulated signals, and Spectral Domain  
- **UI Axes**: For plots of signals and spectra  
- **Edit Field**: For message values, carrier values, and modulation index  

---
