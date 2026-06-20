# Smartphone Screen Defect Detection

## 🚀 Project Goal
Developing a high-precision computer vision model to detect surface defects (scratches, pits, cracks, blemishes) on smartphone screens using industrial-grade annotation techniques.

## 🛠 Progress Log

### Phase 1: Data Sourcing & Curation (COMPLETED)
* **Dataset:** Mobile Phone Defect Segmentation Dataset.
* **Methodology:** Automated data sourcing and curation using Python and `kagglehub`.
* **Result:** Successfully curated 200 high-resolution images, systematically renamed and organized.
* **Status:** ✅ Data is ready and verified.

### Phase 2: Annotation Configuration (COMPLETED)
* **Platform:** CVAT.
* **Labels:** `Scratch`, `Pit`, `Blemish`, `Crack`.
* **Strategy:** Polygon-based annotation for high-precision defect localization.

### Phase 3: Data Analysis & Annotation Strategy (CURRENT)
* **Ground Truth Analysis:** Analyzed existing semantic segmentation masks to standardize annotation protocols.
* **Key Findings:** * `Scratch`: Represented as line-based features (Polyline/Thin-Polygon).
    * `Oil/Stains`: Represented as area-based features (Closed-Polygon).
* **Protocol:** All manual annotations will follow these patterns to ensure compatibility with model training pipelines.
