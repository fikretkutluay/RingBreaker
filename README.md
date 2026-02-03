# 🚀 RingBreaker
## 🎮 Full Gameplay Video
You can watch the high-quality gameplay video on Google Drive:
[👉 Click Here to Watch on Google Drive](https://drive.google.com/drive/folders/1_bzt8MqnKVHso8NUQ0sE9mpfbSYjlYqK?usp=drive_link)
**RingBreaker** is a high-paced, arcade-style mobile game project developed using the Unity engine. The goal is to reach the center by breaking rotating ring layers with perfect timing. This project is built on clean code architecture and optimized game mechanics.

## 🎮 About The Game
The game is based on the principle of destroying concentric or sequential rotating rings with player inputs at the right moments. Despite its simple control scheme, it offers deep gameplay through increasing speed and evolving ring variations.

### Gameplay Mechanics
* **Timing-Based Interaction:** A precise hitting system targeting the weak points of the rings.
* **Progressive Difficulty:** Dynamic changes in ring rotation direction, speed, and complexity as the level progresses.
* **Visual Feedback:** Satisfying destruction effects and "juice" elements that reinforce the impact feel.

## 🛠 Technical Features
This project was developed using industry-standard software principles and modern Unity tools:

* **Engine:** Unity (C#)
* **Software Architecture:**
    * **State-Driven Logic:** Centralized control structures managing the game flow (Menu, In-Game, Game Over).
    * **Object Pooling:** Memory management for frequently instantiated game objects (vFX, ring pieces) to prevent performance drops.
    * **Input Management:** Low-latency touch control system optimized for mobile devices.
* **UI/UX:** Responsive interface design ensuring full compatibility with various screen resolutions.

## 📁 Project Structure
```text
RingBreaker/
├── Assets/
│   ├── Scripts/        # Game logic, controllers, and helper classes
│   ├── Prefabs/        # Reusable game objects (Rings, Effects)
│   ├── Scenes/         # Main game and menu scenes
│   └── Materials/      # Visual styles and shader configurations
