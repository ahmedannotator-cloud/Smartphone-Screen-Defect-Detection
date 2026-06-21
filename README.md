Smartphone Screen Defect Detection
🚀 Project Goal
Developing a high-precision computer vision model to detect surface defects (scratches, pits, cracks, blemishes) on smartphone screens using industrial-grade annotation techniques and AI-assisted workflows.

🛠 Progress Log
Phase 1: Data Sourcing & Curation (COMPLETED)
Dataset: Mobile Phone Defect Segmentation Dataset.

Methodology: Automated data sourcing and curation using Python and kagglehub.

Result: Successfully curated 200 high-resolution images, systematically renamed and organized.

Status: ✅ Data is ready and verified.

Phase 2: Annotation Configuration (COMPLETED)
Platform: CVAT.

Labels: Scratch, Pit, Blemish, Crack.

Strategy: Polygon-based annotation for high-precision defect localization.

Phase 3: Data Annotation & Refinement (COMPLETED)
Tooling: Leveraged CVAT AI Tools to transition from manual to SEMI-AUTO workflows, achieving significant gains in annotation throughput and accuracy.

Quality Control: Standardized annotation protocols for Pits (Area-based) and Scratches (Linear features), ensuring all masks include critical visual context (reflections and shadows) for superior model training.

Volume: Successfully annotated high-precision polygons across the dataset.

Phase 4: Dataset Export & Pipeline Integration (COMPLETED)
Export Format: YOLO 1.1 format for object detection and segmentation.

Data Readiness: Successfully exported training labels, ensuring 1:1 correspondence between images and metadata.

💡 Technical Insights & Methodology
AI-Assisted Workflow: Integrated AI-powered annotation tools to minimize human error and ensure consistency in edge-case detection.

Edge Case Resolution: Developed a strict labeling policy for "white halo" reflections, ensuring the model learns to identify the full footprint of a defect rather than just the core damage.

Optimization: Achieved dataset consistency by maintaining strict polygon-to-boundary adherence, ensuring the model accurately distinguishes between different defect classes based on their physical characteristics.

📂 Repository Structure
/docs/annotation_samples: Contains visual samples of the annotation process and label verification.

/labels: Contains the YOLO-formatted .txt files corresponding to the curated dataset.
