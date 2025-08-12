# Pothole Detection Using YOLOv8


The **Pothole Detection Using YOLOv8** project utilizes computer vision to automatically detect potholes in images and videos.  
Using the YOLOv8 object detection model, the system identifies potholes with bounding boxes and confidence scores, enabling faster road maintenance and improved safety.
This can also be integrated into dashcams or webcams for real-time road assessment.

---

##  Features
- Real-time pothole detection in images and videos.
-  Built with **YOLOv8** (You Only Look Once, version 8).
- Evaluation metrics: **Precision**, **Recall**, **mAP**.
- Custom dataset with annotated potholes.


---

##  Tech Stack
- **Language:** Python  
- **Frameworks/Libraries:**  Ultralytics YOLOv8, OpenCV, NumPy, Matplotlib, Pandas  
- **Annotation Tool:** Roboflow  

---
## Dataset

| Dataset    | Count       |
| ---------- | ----------- |
| Training   | **6385**     |
| Test       | **809**     |
| Validation | **808**     |
| Total      | **8002**      |


**Sample Dataset**
  
  <img width="674" height="306" alt="image" src="https://github.com/user-attachments/assets/c6762540-5dbf-4500-82e0-bdb11e6472c0" />


**Training Data**
  
  <img width="607" height="291" alt="image" src="https://github.com/user-attachments/assets/d65d6f95-61da-4c7f-b565-1e0737b02774" />

**Testing Data**
  
  <img width="630" height="278" alt="image" src="https://github.com/user-attachments/assets/1b1b0efc-1ba7-46c6-b66c-0814b2f62a00" />

**Validation Data**
  
  <img width="623" height="277" alt="image" src="https://github.com/user-attachments/assets/79e77c53-a340-4b10-ba0b-81afe1527b54" />



## Training Performance

**Loss & mAP Curves**
  
  <img width="737" height="368" alt="image" src="https://github.com/user-attachments/assets/08707d71-f623-4623-932a-79b9aca7ec9e" />
  <img width="749" height="365" alt="image" src="https://github.com/user-attachments/assets/07f4bd3c-28df-4fcd-82af-605805a7a4f7" />


------

## Performance Summary
| Metric     | Value       |
| ---------- | ----------- |
| mAP\@0.5   | **88.5%**   |
| Precision  | **87%**     |
| Recall     | **84.4%**   |
| Epochs     | **50**      |
| Image Size | **640×640** |

---

| Input Image                  | Detection Result                       |
| ---------------------------- | -------------------------------------- |
| ![954dfe16-84c7-42a9-9722-a34d38740a2b](https://github.com/user-attachments/assets/caf04200-db89-4faf-8747-422739c6c3ac)
 | <img width="612" height="408" alt="image" src="https://github.com/user-attachments/assets/7cf7881a-c185-4e21-8abf-13667f1e742c" />
 |

