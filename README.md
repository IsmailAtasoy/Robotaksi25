# 🚗 Robotaksi Lane Follower

This repository contains a simplified version of my previous **Robotaksi autonomous driving project**.
All unrelated modules have been removed, and the system is focused entirely on **lane following**.

---

## 📌 Overview

The project implements a basic lane following pipeline using computer vision techniques.
It processes camera input, detects lane lines, and generates steering commands accordingly.

This version is designed to be **lightweight, easy to understand, and modular**.

---

## ⚙️ Features

* Real-time lane detection
* Image processing-based pipeline (OpenCV)
* Steering angle calculation
* Clean and simplified codebase

---

## 🧠 Pipeline

1. Capture image from camera
2. Convert to grayscale
3. Apply edge detection (Canny)
4. Select region of interest
5. Detect lane lines
6. Compute steering angle
7. Send control command

---

## 🗂️ Project Structure

```
Robotaksi25/
├── src/        # Main implementation
├── scripts/    # Helper scripts
├── config/     # Parameters / configs
├── launch/     # Launch files (if ROS is used)
└── README.md
```

---

## 🚀 Installation

```bash
git clone https://github.com/IsmailAtasoy/Robotaksi25.git
cd Robotaksi25
pip install -r requirements.txt
```

---

## ▶️ Usage

```bash
python main.py
```

*(If your entry file is different, update this command accordingly.)*

---

## 🛠️ Requirements

* Python 3.9
* OpenCV
* NumPy

---

## 🎯 Purpose

This repository is intended to demonstrate the **core logic of lane following** in an autonomous driving system without unnecessary complexity.

---

## 👤 Author

Ismail Atasoy

---

## 📌 Notes

* This is a **reduced version** of a larger project
* Designed for learning, experimentation, and demonstration
