# GenAI Music Generation 🎵

## 📌 About
This project demonstrates **AI-driven music generation** using **TensorFlow** and MIDI processing tools. It trains a sequence model to learn note patterns from MIDI files and generate new musical compositions. The system supports converting between MIDI and note sequences, training a generative model, and rendering the output back to MIDI or audio.

---

## ✅ Features
- Load and process **MIDI files** into structured note sequences.
- Build and train a **TensorFlow-based sequence model** (RNN/LSTM).
- Generate new music sequences based on trained patterns.
- Convert generated notes back to **MIDI format** and play as audio using FluidSynth.

---

## 🛠️ Technologies Used
- **Python 3.x**
- **Jupyter Notebook**
- **Libraries:**
  - `tensorflow` for model training
  - `numpy`, `pandas` for data processing
  - `pretty_midi` and `pyfluidsynth` for MIDI and audio rendering

---

## 📂 Project Structure
```
genai_music/
│
├── data/                     # MIDI dataset
├── models/                   # Saved models (if any)
├── genai_music.ipynb         # Main Jupyter notebook
└── README.md                 # Documentation
```

---

## 🔍 How It Works
1. **MIDI Preprocessing:** Extracts features like pitch, step, and duration from MIDI files.
2. **Model Training:** Uses an LSTM-based sequence model in TensorFlow.
3. **Music Generation:** Produces sequences of notes after training.
4. **MIDI Reconstruction:** Converts generated notes back to a playable MIDI file.
5. **Audio Rendering:** Plays audio output using FluidSynth.

---

## ▶️ Getting Started

### ✅ Prerequisites
Install required dependencies:
```bash
apt-get install -y fluidsynth
pip install pyfluidsynth pretty_midi tensorflow pandas numpy
```

### ✅ Steps to Run
1. Clone or download this repository.
2. Open the notebook in Jupyter:
   ```bash
   jupyter notebook genai_music.ipynb
   ```
3. Execute all cells:
   - Preprocess MIDI files.
   - Train the generative model.
   - Generate and export new music.

---

## 🎼 Output
- Generated music is saved as **MIDI files**.
- Playback available using `IPython.display.Audio` and FluidSynth.

---

## 🚀 Future Improvements
- Train on larger and more diverse MIDI datasets.
- Implement **Transformer-based models** for improved sequence generation.
- Add **genre-specific music generation**

- ## Colab link
- https://colab.research.google.com/drive/108QURYWxVzO9OyuDsNWlDyi-fPn53DGi
