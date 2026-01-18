# 🐍 Snake AI – Neural Network + Genetic Algorithm

An intelligent Snake that **learns to play by itself** using a Neural Network evolved through a **Genetic Algorithm**.

![Snake AI Demo](snake-game.gif)  
*(Best generation playing – replace with your own recording)*

## 🎯 What this project shows

- Classic Snake game made with **Pygame**
- Feedforward Neural Network decides every move (24 inputs → hidden → 4 outputs: up/down/left/right)
- Genetic Algorithm evolves population of 3000+ snakes
- Real-time visualization of learning progress
- Saves & loads best performing snakes
- Nice GUI showing generation, score, fitness & more

## 🔥 Features

- 24 smart inputs (danger & food in 8 directions + current direction)
- Population size: 3000 (configurable)
- Mutation rate: 2%, crossover rate: 80% (tunable)
- Fitness = score × score + steps survived (encourages both surviving & eating)
- Auto-adjusts game speed for better watching
- Can run training silently or show beautiful real-time visualization

## 🚀 Quick Start

```bash
# 1. Clone the project
git clone https://github.com/yourusername/snake-ai.git
cd snake-ai

# 2. Install required packages (run in PowerShell / CMD)
pip install pygame numpy matplotlib torch

# 3. Run (choose one)
python main.py          # Start training + watch progress (recommended)
python gui.py           # Watch the best saved snake play (great for demo)
📊 Expected Results
After 50–200 generations (depends on luck & hyperparameters):

Early generations: ~5–15 points
Good runs after 100+ gens: 50–120+ points average
Best snakes often reach 150–400+ points



🛠️ Tech Stack

Python 3.8+
Pygame – game engine
NumPy – fast math
Matplotlib – training graphs
(Optional) PyTorch – if you want to experiment with modern NN
<img width="1200" height="767" alt="image" src="https://github.com/user-attachments/assets/e08f49af-3779-4494-9a21-2adb3e3521b3" />

