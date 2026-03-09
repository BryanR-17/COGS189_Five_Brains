# **COGS 189 - Five Brains (Linguistic Interference EEG Project)**

This repository contains the analysis pipeline for ouor **COGS 189 final project**, which investigates how different types of background audio influence cognitive processing. Using EEG recordings, we analyze how **music with understood lyrics, non-understood lyrics, instrumental music, and speech** affect cognitive load during listening task.

Cogntive engagement is estimated using **frequency-domain EEG featrues**, specifically **Alpha (8-12 Hz)** and **Beta (13-30 Hz)** band power.
---

# Project Structure

```
COGS189_Five_Brains/
│
├── notebooks/
│   ├── 01_setup_validation.ipynb
│   └── 02_feature_stats_ml_visual.ipynb
│
├── Preprocessed/                  # Preprocessed EEG subject files (.mat)
├── requirements.txt               # Python dependencies
├── README.md                      # Project overview and instructions
└── .gitignore
```

---

### **Team Members**

| Name                | PID       | Email                  |
| ------------------- | --------- | ---------------------- |
| **Sabine Loaiza**   | A17834935 | sloaizachable@ucsd.edu |
| **Avalon Andresen** | A17794154 | aandresen@ucsd.edu     |
| **Bryan Ramirez**   | A17302269 | b9ramirez@ucsd.edu     |
| **Kayla Li**        | A18630941 | chl324@ucsd.edu        |
| **JiJi Choi**       | A######## | jic169@ucsd.edu        |

### **Getting Started**

1. Clone the repository:
   ```bash
   git clone https://github.com/BryanR-17/COGS189_Five_Brains.git
   cd COGS189_Five_Brains
   ```

### **Contributing**

1. Make changes and push to your branch:
   ```bash
   git add .
   git commit -m "Your commit message"
   git push origin <branch-name>
   ```

### **Dataset**

We use the public **“EEG data of continuous listening of music and speech”** dataset from Aalborg University:

```bash
https://vbn.aau.dk/en/datasets/eeg-data-of-continuous-listening-of-music-and-speech/
```
