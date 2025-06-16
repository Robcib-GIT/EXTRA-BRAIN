# 🔍 Quadruped Robot Perception – YOLOv8 Dataset and Global Model

This repository contains a collection of datasets and trained YOLOv8 models designed to improve the perception capabilities of a quadruped robot navigating in disaster scenarios. The system integrates object segmentation, terrain classification, and victim identification using RGB data, with a final Global Model that integrates all datasets.

---

## 🧠 Global Objective

Train a unified perception system for a quadruped robot capable of:
- Identifying victims in cluttered or shed environments
- Classifying soil and terrain types
- Detecting static and dynamic obstacles

---

## 🗂️ Project Structure

The following submodules were trained with YOLOv8 object segmentation and contribute to the final **GLOBAL MODEL**:

### 🌍 TERRAIN DETECTION
- Identifies natural terrain types. - Differentiates between terrain materials.
- Detects safe and unsafe ground areas

### 🛖 SHED SCENARIOS
- Multiple sheds with different victim and object configurations
- Victims in confined spaces 

### 🧍 VICTIM DETECTION
- Victims in open and urban settings
- Victims and obstacles in controlled environments

---

## 🧪 Final Integration: Global Model

All datasets and trained YOLOv8 models were combined to build a **GLOBAL MODEL**

This model was trained with:
- 🧠 YOLOv8m-sec backbones
- 🔄 Fused labels and dataset extension
- 🎯 Robust annotation across different environments

---

## 📁 File Organization
