# 📱 ARNav: Augmented Reality Indoor Navigation System  

[![Unity](https://img.shields.io/badge/Built%20With-Unity-FF6C37?logo=unity&logoColor=white)](https://unity.com/)  
[![ARCore](https://img.shields.io/badge/Powered%20By-Google%20ARCore-blue?logo=google)](https://developers.google.com/ar)  
[![Platform](https://img.shields.io/badge/Platform-Android-green?logo=android)](https://www.android.com/)  
[![License](https://img.shields.io/badge/License-MIT-brightgreen)](LICENSE)  

---

## 🗺️ Navigating Indoor Spaces Using Augmented Reality  

**ARNav** is a mobile-based **Augmented Reality (AR)** navigation assistant designed for **complex indoor environments** such as college campuses. It uses **markerless AR technology** to provide real-time navigation without requiring physical markers, enabling users to explore spaces intuitively.  

By leveraging **3D space recognition**, **image-based localization**, and **ARCore-powered visualization**, ARNav creates a flexible, interactive, and immersive navigation experience.  

---

## 🚀 Features
- 🔥 **Markerless AR Tracking**: Uses a vision-based system for flexibility (no QR codes or physical markers required).  
- 📍 **3D Mapping & Localization**: Builds a point cloud of the campus and determines user location within it.  
- 📱 **Interactive UI**: Allows users to choose destinations, switch visualization modes, and navigate floors easily.  
- 🗺️ **Immersive Navigation**: Overlays AR path indicators within the real-world view for intuitive wayfinding.  
- ⚙️ **Debug Options**: Includes adjustable height of path indicators, floor switching, and visibility toggles.  

---

## 🖇️ Workflow

1. **Mapping**  
   - Acquire 3D data models of the environment.  
   - Generate point clouds for indoor spaces.  

2. **Localization**  
   - Determine user position within multiple point clouds.  
   - Enable dynamic wayfinding based on location.  

3. **Visualization**  
   - Render AR paths, directions, and interactive elements using Unity and ARCore.  

---

## 📱 Working Model  

The ARNav working prototype is implemented as an **Android application** developed with **Unity**:  
- 📂 **Three Panels**:
  - **Path Visualization**: Toggle path rendering and visibility.  
  - **Debug Panel**: Adjust path indicator height and other parameters.  
  - **Floor Switcher**: Change floors dynamically.  

- 🧠 **3D Space Recognition**: Recognizes indoor layouts and eliminates physical markers.  
- 🏫 **Campus Model Integration**: Built using the 3D model of the college campus for realistic navigation.  

---

## 🛠️ Tech Stack  

| Technology         | Purpose                                   |
|---------------------|-------------------------------------------|
| Unity               | Game engine for AR application development |
| ARCore              | Markerless AR tracking and visualization |
| C#                  | Scripting in Unity                       |
| Blender/3DS Max     | 3D modeling for campus layouts            |
| Android SDK         | Mobile platform deployment                |

---

## 📥 Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/ARNav.git
   cd ARNav


![Untitled (2) (1)](https://github.com/Caspian4/ARNav/assets/124158194/c110562b-d870-41c2-ac13-3af3fdbecdad)

2. Open in Unity
Open the project folder in Unity Hub.
Make sure ARCore XR Plugin is installed via Unity Package Manager.

3. Build for Android
Set up Android SDK in Unity.
Build and run the APK on your Android device.

![a](https://github.com/Caspian4/ARNav/assets/124158194/fafdc737-b0ec-4e9a-b539-e19a0d331a5d)

👨‍💻 About the Author
Developed with ❤️ by Riddhi Singh.
For collaboration or suggestions, feel free to reach out!

📜 License
This project is licensed under the MIT License.
