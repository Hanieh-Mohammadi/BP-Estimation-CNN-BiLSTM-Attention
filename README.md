# CNN–BiLSTM–Attention Framework for Blood Pressure Estimation

This repository provides the implementation of the proposed deep learning framework described in our manuscript:

**"Cuffless Blood Pressure Waveform Estimation Using CNN–BiLSTM with Attention Mechanism"**  
(Submitted to IEEE Access, currently under review)

---

## Overview

The proposed model estimates continuous arterial blood pressure (ABP) waveforms from photoplethysmography (PPG) signals using:

- 6-layer CNN feature extractor  
- 2-layer BiLSTM temporal modeling  
- Attention mechanism  
- Fully connected BP waveform reconstruction  

---

## Dataset

Experiments were conducted using the public **MIMIC-III waveform database**.


## Requirements

Install dependencies using:

```bash
pip install -r requirements.txt

