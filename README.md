<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Inter&weight=800&size=32&duration=2800&pause=800&color=6C63FF&center=true&vCenter=true&width=600&lines=%F0%9F%8E%AE+Game+Recommender+System;Mood-Based+AI+Recommendations;CNN+%2B+RNN+%2B+Random+Forest;Find+Your+Next+Favorite+Game" alt="Typing SVG" />
</div>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" />
  <img src="https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/Numpy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
</p>

<p align="center">
  <img src="https://img.shields.io/github/stars/Ezaz20001/Game_recommender_system?style=social" />
  <img src="https://img.shields.io/github/forks/Ezaz20001/Game_recommender_system?style=social" />
  <img src="https://img.shields.io/badge/license-MIT-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/PRs-Welcome-brightgreen?style=flat-square" />
</p>

---

## 🧠 Overview

An intelligent **Game Recommender System** that suggests video games based on the user's **mood and emotional state**. Built from scratch using **CNN, RNN, and Random Forest** models, the system takes natural language mood input and generates personalized game recommendations with explainable confidence scores.

> 🎯 **Mission:** Take the guesswork out of choosing what to play next — your mood is the only input you need.

---

## ✨ Features

| Feature | Description |
|---|---|
| 🧠 **Mood-Based AI** | Recommends games based on how you're feeling (happy, sad, angry, excited, etc.) |
| 🔀 **Multi-Model Ensemble** | Combines CNN + RNN, Random Forest, and custom logic for higher accuracy |
| 📊 **Confidence Scoring** | Shows model confidence behind each recommendation |
| 🎮 **150+ Games** | Trained on a curated dataset of popular titles across all genres |
| 🖥️ **Interactive UI** | Clean interface for mood input and game suggestions |
| 🔌 **Extensible** | Easy to add new games, moods, or retrain with custom data |

---

## 🏗️ Architecture

```
User Mood Input (text)
        │
        ▼
┌─────────────────┐
│   Tokenizer     │  ───  Tokenizes mood words → numerical indices
└────────┬────────┘
         │
         ▼
┌─────────────────┐
│  CNN + RNN      │  ───  Deep learning ensemble
│  Random Forest  │       for mood-to-game mapping
└────────┬────────┘
         │
         ▼
┌─────────────────┐
│  Label Classes  │  ───  Maps predictions → game titles
└────────┬────────┘
         │
         ▼
┌─────────────────┐
│  Recommendation │  ───  Sorted by confidence score
│    Engine       │
└─────────────────┘
```

---

## 🛠️ Tech Stack

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" />
  <img src="https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white" />
  <img src="https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" />
</p>

---

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- pip

### Installation

1. **Clone the repo**
   ```sh
   git clone https://github.com/Ezaz20001/Game_recommender_system.git
   cd Game_recommender_system
   ```

2. **Create virtual environment (recommended)**
   ```sh
   python -m venv venv
   source venv/bin/activate  # Linux/Mac
   venv\Scripts\activate     # Windows
   ```

3. **Install dependencies**
   ```sh
   pip install tensorflow numpy pandas scikit-learn streamlit
   ```

4. **Run the app**
   ```sh
   streamlit run app.py
   ```

   *(If `app.py` is not present, you can use the model directly with the provided artifacts)*

---

## 📁 Project Structure

```
Game_recommender_system/
├── cnn_mood_game_model.h5   # Trained CNN + RNN model (TensorFlow)
├── label_classes.json       # 150+ game titles for predictions
├── tokenizer.json           # Mood word → index mapping
├── .gitignore               # Ignored files
└── README.md                # This file
```

---

## 🎮 Supported Moods

| Mood | Example Games Recommended |
|:---:|---|
| 😊 **Happy** | Animal Crossing, Stardew Valley, Mario Odyssey |
| 😢 **Sad** | Gris, Spiritfarer, Firewatch |
| 😠 **Angry** | DOOM Eternal, Mortal Kombat, Hatred |
| 😨 **Fear** | Outlast, Alien Isolation, Amnesia |
| 🤩 **Excited** | Apex Legends, Rocket League, Cyberpunk 2077 |
| 😐 **Neutral** | Minecraft, Tetris Effect, Mini Metro |
| 😴 **Bored** | Celeste, Baba Is You, Portal |
| 😰 **Anxious** | Journey, Flower, Abzu |
| 😵 **Stressed** | Stardew Valley, Slime Rancher, Unpacking |
| 🤢 **Disgust** | Carrion, Scorn, The Last of Us |

---

## 🔮 Future Roadmap

- [ ] Add `app.py` with Streamlit UI for easy interaction
- [ ] Integrate real-time game API data (IGDB / Steam)
- [ ] Support multi-mood input ("I'm happy and excited")
- [ ] User feedback loop to improve recommendations
- [ ] Dark / light theme toggle
- [ ] Deploy to Hugging Face Spaces or Streamlit Cloud
- [ ] Git LFS for model file management

---

## 🤝 Contributing

Contributions make the open-source community amazing! Any contributions are **greatly appreciated**.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add AmazingFeature'`)
4. Push (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

## 🙏 Acknowledgements

- [TensorFlow](https://www.tensorflow.org/) for the deep learning framework
- [scikit-learn](https://scikit-learn.org/) for ML utilities
- [Streamlit](https://streamlit.io/) for the web UI framework
- All game developers who create the amazing titles in this dataset 🎮

---

<p align="center">
  Made with 🧠 + ❤️ by <a href="https://github.com/Ezaz20001">Amad Uddin Ezaz</a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=10&height=100&section=footer" />
</p>
