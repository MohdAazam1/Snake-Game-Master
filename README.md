# 🎮 Game Using Hand Gesture

This project is a **Java-based game** that allows players to control gameplay using **hand gestures** instead of traditional keyboard or mouse input. By leveraging **computer vision techniques** (such as OpenCV for Java), the game tracks hand movements through a webcam and maps them to in-game actions.  

---

## 🚀 Features
- Real-time **hand gesture recognition** using webcam  
- **Interactive gameplay** without physical controllers  
- Fun, engaging, and innovative way to play classic games  
- Built in **Java** for cross-platform compatibility  

---

## 🛠️ Technologies Used
- **Java** (Core game logic)  
- **OpenCV (Java bindings)** – for hand tracking  
- **AWT / Swing / JavaFX** – for game interface (if used)  

---

## 📦 Installation
1. Install **Java JDK 8+** on your system.  
2. Install **OpenCV (Java bindings)** if not already installed.  
   - Download from: [OpenCV Releases](https://opencv.org/releases/)  
   - Add the OpenCV `.jar` file to your project’s classpath.  
   - Place the native OpenCV binaries (`.dll` / `.so`) in your system path.  

---

## ▶️ How to Run
1. Clone this repository or download the source code:  
   ```bash
   git clone https://github.com/your-username/Game_Using_Hand_Gesture.git
   ```
2. Navigate to the project folder.  
3. Compile the code:  
   ```bash
   javac Main.java
   ```
4. Run the game:  
   ```bash
   java Main
   ```
5. Allow camera access. Move your hand in front of the webcam to control the game!  

---

## 📂 Project Structure
```
Game_Using_Hand_Gesture/
│── src/
│   ├── Main.java          # Entry point
│   ├── Game.java          # Game logic
│   ├── HandTracker.java   # Hand gesture recognition
│── lib/                   # OpenCV JAR + native binaries
│── README.md              # Documentation
```

---

## 🔮 Future Improvements
- Support **multiple games** controlled by gestures  
- Add more **gesture mappings** (e.g., thumbs up, two hands)  
- Improve tracking accuracy and reduce lag  

---

## 👨‍💻 Author
Developed by **[Your Name]** ✨  
