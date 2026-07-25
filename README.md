Deep Learning Models for Tire Code Recognition and Tread Depth Measurement for Wear Analysis via a Mobile Application
---
A Term Paper Presented in Partial Fulfillment of the Requirements of the Course 225393 Computer Science Project Second Semester, Academic Year 2025 University of Phayao 
---
Key Objectives
- To develop deep learning models (CNN) to detect and recognize tire sidewall codes (such as DOT code and tire size).
- To implement YOLO11 combined with image processing techniques (Mathematical Morphology, Polynomial Regression) to measure tire tread depth.
- To calculate tire wear levels, estimate remaining service life (years/kilometers), and assess safe driving usability.
- To send alert notifications via a mobile application when tires are near expiration or excessively worn out.
---
Technology Stack
- AI & Computer Vision: CNN for sidewall code detection and text recognition (CRNN), and YOLO11 integrated with statistical filtering (IQR, Z-Score) for tread depth calculation.
- System Architecture: Frontend developed using Flutter (Dart), Backend powered by FastAPI (Python), and database managed via SQLite.
- Dataset: Consists of 1,247 tire images in total (947 sidewall images and 300 tread depth images).
---
erformance & Evaluation
- Tire Code Detection Model: Achieved mAP@0.5 of 0.9712, Precision of 1.00, and Recall of 0.9512.
- Tire Code Recognition Model (CRNN): Obtained a Character Error Rate (CER) of 5.59% and Sequence Accuracy of 90.06%.
- Tread Depth Measurement Model: Recorded a Mean Absolute Error (MAE) of 0.8 mm, with roughly 90% of data falling within a ±1.5 mm error margin.
- User Evaluation: Overall user satisfaction score from 30 testers was rated at 4.383 out of 5.00.
---
Limitations & Challenges
- Data collection for tread depth required manual photo capture paired with digital gauges.
- Environmental variables like lighting conditions, photo angles, tire tread variations, and smartphone camera quality can affect measurement precision.
