# **Autonomous Vehicles for Bangladesh Roads – Kaggle Competition 🚗**

This repository documents my participation in the **"Autonomous Vehicles for Bangladesh Roads" Kaggle competition**, part of the **SUST CSE Carnival: Deep Learning Event DL Enigma 1.0**. This exciting challenge focuses on advancing autonomous driving technology tailored for the unique driving environments of Bangladesh.

---

## **Competition Overview**

Participants in this challenge were tasked with tackling the complex problem of **object detection** in diverse driving scenarios across **9 districts of Bangladesh**. The competition leveraged **BadODD (Bangladeshi Autonomous Driving Object Detection Dataset)**, a comprehensive dataset specifically designed to address the intricacies of Bangladeshi roads.

The goal of the competition was to build and fine-tune innovative object detection models that could contribute to **autonomous navigation technology** for self-driving cars in Bangladesh.

---

## **Models and Approaches**

### **Models Used**

1. **Detectron2**  
   - Fine-tuned using **various augmentations** for enhanced performance.  
   - Delivered the **best results** for me.

2. **YOLO (You Only Look Once)**  
   - Experimented with multiple configurations for object detection.  
   - Provided competitive results but slightly underperformed compared to **Detectron2**.

---

### **Key Techniques**

- **Data Augmentation**: Applied diverse augmentation strategies in **Detectron2** to improve model robustness, including:  
  - Rotation  
  - randomflip 
  - random brightness 

- **Fine-Tuning**: Both models were fine-tuned extensively to adapt to the unique characteristics of the **BadODD dataset**.

---

## **Results**

- **Best Performing Model**:  
  **Detectron2**, fine-tuned with tailored augmentations, achieved the highest accuracy for object detection tasks.  

- **YOLO**:  
  A solid performer but did not surpass **Detectron2** in terms of overall accuracy and generalization.

---

**model link : https://www.kaggle.com/datasets/samratabduljalil/abc-final-model-weight

