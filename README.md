# 🚗 Persian License Plate Recognition System (PLPR)

The Persian License Plate Recognition (PLPR) system is a state-of-the-art solution designed for detecting and recognizing Persian license plates in images and video streams. Leveraging advanced deep learning models and a user-friendly interface, it ensures reliable performance across different scenarios.

## 🔍 Overview

This system aims to tackle the unique challenges associated with Persian license plate detection and recognition, offering high accuracy and efficiency. It's well-suited for applications in traffic monitoring, automated vehicle identification, and similar fields.

## ✨ Key Features

- **Advanced Detection**: Utilizes YOLOv5 models for high-accuracy license plate detection.
- **Persian Character Recognition**: Custom-trained models ensure precise recognition of Persian characters.
- **Real-Time Processing**: Capable of processing live video feeds in real-time.
- **User-Friendly GUI**: Intuitive graphical user interface simplifies interactions with the system.
---
![explain main gui](/parts.jpg)
- The main view to show the input (video/camera)
- Rectangle around the detected plate 
- Image of the detected plate
- The text extracted from plate image
- Name of the owner of the plate
- Status of the plate which is (Allowed,Not Allowed, Non Registered)
- The table of last 10 enteries which we can add a non registered plate or see the information of the owner
---
![explain main flowchart](/flowchart.png)
## 📋 Prerequisites

- Python 3.8+
- Pip for Python package management

## 🚀 Getting Started

### 🔧 Installation

1. Clone the repository and navigate to its directory:
   ```bash
   git clone https://github.com/mtkarimi/smart-resident-guard.git
   cd smart-resident-guard
   ```
2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

### ▶️ Running the Application

Launch the application with the following command:
```bash
python home-yolo.py
```

## 🛠️ Usage

The system's GUI enables users to upload and process images or video streams, displaying detected license plates and recognized text. It also allows for parameter adjustments to optimize performance.

## 📖 Learn More in the Wiki

For a deep dive into the PLPR system's architecture, model training, and advanced usage, check out our [Wiki](https://github.com/mtkarimi/smart-resident-guard/wiki). It's a comprehensive resource for users and developers alike.

## 📚 Additional Resources

Explore the `pdf-research` directory for research papers and articles on LPR technologies, offering insights into the techniques and algorithms behind the system.

## 💙 Special Thanks

Heartfelt thanks to the open-source projects and communities that have made this project possible. Special mentions include:

- **YOLOv5** and **PyTorch** for the core detection and recognition models.
- **PySide6** and **OpenCV** for the application interface and image processing capabilities.
- **Pillow** for enhanced image manipulation.

## 📦 Repositories Used

- YOLOv5: [GitHub](https://github.com/ultralytics/yolov5)
- PyTorch: [GitHub](https://github.com/pytorch/pytorch)
- PySide6: [GitHub](https://github.com/PySide/PySide6)
- OpenCV: [GitHub](https://github.com/opencv/opencv)
- Pillow: [GitHub](https://github.com/python-pillow/Pillow)

## 🙏 Acknowledgments

This project stands on the shoulders of giants within the AI and open-source communities. Their dedication to sharing knowledge and tools has been invaluable.

## 📄 License

GPL-3.0. See the [LICENSE](LICENSE) file for details.


### Individual Contributions

I also want to thank the following individuals for their direct contributions, advice, or resources that have been instrumental in the success of this project:

- [Mahdi Rahmani](https://github.com/MahdiRahmani)
- [Meftun AKARSU](https://github.com/mftnakrsu)

### Datasets
- [IR-LPR](https://github.com/mut-deep/IR-LPR)
- [Iranis-dataset](https://github.com/alitourani/Iranis-dataset)
- [ILPR](https://github.com/amirmgh1375/iranian-license-plate-recognition)

---
![explain main resident management](/people.jpg)
![explain main enterance management](/ent.png)

