# 🚗 Feature Extraction and Classification of Moving Vehicles on Highways

Intelligent vehicle detection, tracking, and classification system designed to operate under challenging environmental conditions like fog, rain, and low visibility. This project leverages computer vision and deep learning to analyze traffic videos, predict risky driving behavior, and help reduce accidents on highways.

## ✨ Features

- **Real-time Vehicle Detection**: Detects vehicles in adverse weather conditions
- **Advanced Tracking**: Maintains consistent tracking across frames
- **Vehicle Classification**: Categorizes vehicles by type (car, truck, motorcycle, etc.)
- **Risky Behavior Prediction**: Identifies unsafe driving patterns to prevent accidents
- **Weather Resilience**: Optimized for fog, rain, and low visibility scenarios
- **High Accuracy**: Utilizes state-of-the-art deep learning models

## 🛠️ Tech Stack

- **Computer Vision**: OpenCV, PIL
- **Deep Learning**: TensorFlow/Keras, PyTorch, YOLOv5
- **Processing**: NumPy, SciPy
- **Video Analysis**: FFmpeg
- **Environment**: Python 3.8+

## 📋 Requirements

```bash
pip install opencv-python tensorflow torch torchvision yolov5 numpy scipy
```



## 📊 Model Architecture

The system uses a multi-stage pipeline:

1. **Detection Stage**: YOLOv5 for real-time vehicle detection
2. **Feature Extraction**: Extracts visual features (color, shape, size)
3. **Tracking Stage**: Deep SORT for multi-object tracking
4. **Classification Stage**: CNN for vehicle type classification
5. **Behavior Analysis**: Pattern recognition for risky driving detection


## 📄 License

This project is licensed under the MIT License - see LICENSE file for details.

## 👨‍💻 Author

**Jigyasa** - [GitHub Profile](https://github.com/Jigyasa-2606)

## 🙏 Acknowledgments

- YOLOv5 team for the detection model
- Deep SORT authors for tracking algorithm
- OpenCV community for computer vision tools

## 📞 Contact & Support

For issues, questions, or suggestions:
- Open an issue on GitHub
- Check existing documentation
- Review project wiki

---

⭐ If this project helps you, please consider giving it a star!
