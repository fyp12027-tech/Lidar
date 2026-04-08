# [Sub-Module] Surface Crack Detection AI

## Context in FYP
This module is a core component of our multi-sensor suite, designed to identify structural fractures on concrete and metal surfaces. It works in tandem with the LiDAR and Thermal units to provide comprehensive site analysis.

## Implementation Details
- **Development Environment:** Google Colab.
- **Framework:** YOLOv8.
- **Data Source:** Roboflow (All-type-crack-dataset).
- **Functionality:** Real-time identification and localization of surface defects.

##  Folder Contents
- `Crack_Detection_Model.ipynb`: Full training pipeline and inference logs.
- `best.pt`:Model weights for integration.

##  Status
The training environment and dataset mapping are fully configured. Initial tests show successful detection of surface fractures across various lighting conditions.
