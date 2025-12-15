# 🤟 Esharty (إشارتي)

> *Bridging communication gaps through AI-powered sign language recognition*

## 📖 Overview

**Esharty** (meaning "My Sign" in Arabic) is an innovative AI-powered mobile application designed to break down communication barriers for the deaf and mute community.

Built with **Flutter** and **FlutterFlow**, and powered by a **TensorFlow Lite** computer vision model, Esharty uses real-time camera input to recognize sign language hand gestures and instantly convert them into readable text, enabling seamless communication between deaf/mute individuals and those who don't understand sign language.

---

## ✨ Key Features

### 🎥 **Real-Time Sign Language Recognition**
- Uses device camera to capture hand gestures in real-time
- Powered by TensorFlow Lite for fast, on-device inference
- Accurate gesture detection and classification
- Works offline without internet connection

### 🧠 **AI-Powered Computer Vision**
- Custom-trained TensorFlow Lite model
- Optimized for mobile performance
- Supports multiple sign language gestures
- Continuous learning and model improvements

### 💬 **Text Conversion & Display**
- Instant conversion of recognized gestures to text
- Clear, readable output interface
- History of converted phrases
- Copy-to-clipboard functionality

### 🎨 **User-Friendly Interface**
- Simple, intuitive camera-based interface
- Minimal learning curve
- Accessible design for all users
- Smooth animations and transitions

### ♿ **Accessibility Focus**
- Specifically designed for deaf and mute users
- Helps bridge communication gaps
- Promotes inclusion and independence
- Enables easier interaction with non-signers

---

## 🛠️ Tech Stack

- **Framework**: Flutter (Dart)
- **Development Platform**: FlutterFlow
- **AI/ML**: TensorFlow Lite (computer vision model)
- **Computer Vision**: Real-time hand gesture recognition
- **Camera Integration**: Flutter camera plugin
- **Platforms**: Android & iOS

---

## 🚀 Getting Started

### Prerequisites

- Flutter SDK (stable channel)
- Dart SDK
- Android Studio / Xcode (for mobile development)
- TensorFlow Lite dependencies
- Device with camera access

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/mahmoud-talbawy/Esharty.git
   ```

2. **Navigate to the project directory**
   ```bash
   cd Esharty
   ```

3. **Install dependencies**
   ```bash
   flutter pub get
   ```

4. **Run the app**
   ```bash
   flutter run
   ```

5. **Grant camera permissions** when prompted on first launch

---

## 📂 Project Structure

```
Esharty/
├── lib/              # Main application code
│   ├── pages/        # App screens and UI
│   ├── components/   # Reusable widgets
│   ├── models/       # TensorFlow Lite model integration
│   └── utils/        # Helper functions
├── assets/           # TensorFlow Lite models and labels
├── images/           # App images and icons
├── android/          # Android-specific configuration
├── ios/              # iOS-specific configuration
├── test/             # Unit and widget tests
└── pubspec.yaml      # Project dependencies
```

---

## 🎯 Use Cases

- **Personal Communication** - Help deaf/mute individuals communicate with family and friends
- **Education** - Support learning and teaching sign language
- **Healthcare** - Facilitate communication in medical settings
- **Customer Service** - Enable better service for deaf/mute customers
- **Emergency Situations** - Quick communication in critical moments
- **Workplace Inclusion** - Promote accessibility in professional environments

---

## 🔬 How It Works

1. **Camera Capture** - App accesses device camera to capture real-time video feed
2. **Gesture Detection** - TensorFlow Lite model processes each frame to detect hand gestures
3. **Classification** - Recognized gestures are classified into specific sign language symbols
4. **Text Conversion** - Classified gestures are converted into corresponding text
5. **Display Output** - Converted text is displayed on screen for the other person to read

---

## 📱 Screenshots

*Coming soon! Screenshots will showcase the camera interface, gesture recognition in action, and text output display.*

---

## 🤝 Contributing

Contributions are welcome! Whether you want to:

- Improve gesture recognition accuracy
- Add support for more sign language gestures
- Enhance the ML model performance
- Improve UI/UX design
- Add support for different sign language systems (ASL, BSL, etc.)
- Optimize for better performance
- Fix bugs or improve code quality

Feel free to open an **issue** or submit a **pull request**.

---

## 🌍 Impact & Vision

Esharty aims to create a more inclusive world by:

- **Breaking Communication Barriers** - Making it easier for deaf and mute individuals to communicate
- **Promoting Independence** - Reducing reliance on interpreters for everyday interactions
- **Raising Awareness** - Highlighting the importance of accessibility in technology
- **Empowering Communities** - Giving a voice to those who communicate through sign language

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 📧 Contact

For questions, suggestions, or collaboration:

- **GitHub**: [@mahmoud-talbawy](https://github.com/mahmoud-talbawy)
- **Issues**: [Report a bug or request a feature](https://github.com/mahmoud-talbawy/Esharty/issues)

---

## 🙏 Acknowledgments

Special thanks to the deaf and mute community for inspiring this project and to all contributors working towards a more accessible future.

---

<p align="center">Made with ❤️ for accessibility and inclusion</p>
<p align="center">Breaking barriers, one gesture at a time 🤟</p>
