# Lane Detection

## 🌍 Language Options / Dil Seçenekleri
- 🇹🇷 [Türkçe](README.md)
- 🇺🇸 [English](README_EN.md) (Current)

---

This project is a Python application developed for detecting lane lines in video files.

## 📸 Screenshots / Ekran Görüntüleri


---

## Features
- Lane line detection in video files
- Image processing using OpenCV
- Real-time analysis
- Advanced computer vision algorithms

## Installation
```bash
pip install -r requirements.txt
```

## Usage
```bash
python Yol_cizgisi_tespiti.py
```

## Requirements
- Python 3.7+
- OpenCV
- NumPy

## About the Project
This project is a lane detection system developed to enhance driving safety. Using OpenCV and NumPy libraries, lane lines are detected in real-time from video streams.

## How It Works
The system processes video frames through several stages:
1. **Image Preprocessing**: Grayscale conversion and noise reduction
2. **Edge Detection**: Canny edge detection algorithm
3. **Region of Interest**: Focusing on the road area
4. **Line Detection**: Hough transform for line detection
5. **Lane Tracking**: Filtering and smoothing detected lines

## Project Structure
```
├── Yol_cizgisi_tespiti.py    # Main application file
├── video1.mp4                # Sample video 1
├── video2.mp4                # Sample video 2
├── requirements.txt           # Python dependencies
├── README.md                 # Turkish documentation
├── README_EN.md              # English documentation
├── screenshots/              # Screenshots folder
└── LICENSE                   # MIT License
```

## Contributing
We welcome contributions! Please feel free to:
- Open an issue for bugs or feature requests
- Submit pull requests with improvements
- Suggest enhancements or optimizations

## Development Setup
1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`
3. Run the application: `python Yol_cizgisi_tespiti.py`

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments
- OpenCV community for computer vision tools
- NumPy for numerical computing capabilities
- Contributors and testers of this project
