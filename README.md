# Accuracy Assessment of LULC Classification – Kamrup Rural (2025)

## 📌 Project Overview / Problem Statement

Land Use and Land Cover (LULC) maps derived from satellite imagery play a crucial role in environmental monitoring, land management, and regional planning. However, classification outputs may contain inaccuracies due to spectral similarity, mixed pixels, and algorithm limitations.  

To ensure the reliability of classified LULC maps, **accuracy assessment** is essential. This project evaluates the accuracy of a **2025 LULC classification for Kamrup Rural District, Assam**, using standard statistical measures such as the confusion matrix and Kappa coefficient.

---

## 🎯 Objective

The objectives of this project are to:
- Assess the **accuracy of the LULC classification**
- Calculate **Producer’s Accuracy, User’s Accuracy, Overall Accuracy, and Kappa Coefficient**
- Evaluate the **reliability of the classified LULC map** for further spatial analysis and decision-making

---

## 📍 Study Area

The study area is **Kamrup Rural District**, located in the state of **Assam, India**.

- Latitude: ~25°40′N – 26°40′N  
- Longitude: ~90°00′E – 91°40′E  
- Dominant land cover types include agriculture, dense forest, grasslands, sandbars, settlements, and water bodies  
- Influenced by the **Brahmaputra River system**, making LULC assessment environmentally significant

📌 *Refer to the map image included in this repository for spatial extent.*

---

## 🗂️ Data Sources

| Data | Source |
|----|----|
| Satellite imagery | Sentinel-2 MSI (ESA Copernicus) |
| Reference / validation points | Google Earth & field interpretation |
| Administrative boundary | Survey of India / Assam GIS sources |
| Base maps | OpenStreetMap |

### 🔗 Data Links
- Sentinel-2: https://scihub.copernicus.eu  
- Google Earth: https://earth.google.com  
- OpenStreetMap: https://www.openstreetmap.org  

---

## 🛠️ Tools & Methods

### Software Used
- ArcGIS 10.8
- Microsoft Excel

### Methodology
1. Preparation of supervised LULC classification
2. Generation of random reference points for each class
3. Validation using high-resolution imagery
4. Creation of confusion matrix
5. Calculation of accuracy metrics:
   - Producer’s Accuracy
   - User’s Accuracy
   - Overall Accuracy
   - Kappa Coefficient
6. Visualization and interpretation of results

---

## 🗺️ Key Outputs

- LULC Accuracy Assessment Map (2025)
- Confusion Matrix
- Accuracy statistics table
- Overall Accuracy and Kappa Coefficient values

---

## 📊 Results & Interpretation

- **Overall Accuracy:** 79%  
- **Kappa Coefficient:** 0.75  

The Kappa value indicates a **good level of agreement** between classified data and reference data.  
Dense Forest and Waterbody classes show high accuracy, while moderate confusion exists between agriculture, grasslands, and settlements due to spectral similarity.  

Overall, the classification is **reliable and suitable for regional-scale applications**.

---

## 📘 What I Learned

- Practical application of **accuracy assessment techniques**
- Importance of validation data in remote sensing
- Interpretation of Kappa statistics
- Identification of classification uncertainties in GIS projects

---

## 🚀 Future Improvements

- Use of higher-resolution satellite imagery
- Inclusion of field-collected GPS points
- Application of machine learning classifiers (Random Forest, SVM)
- Multi-seasonal analysis for improved class discrimination
- Increasing validation sample size per LULC class

---

## ✅ Conclusion

The accuracy assessment confirms that the **2025 LULC classification of Kamrup Rural District is of good quality** and can be confidently used for environmental monitoring, land-use planning, and further GIS-based studies.
