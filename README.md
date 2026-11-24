# DeepForge: AI-Driven Image Judging System

## 📋 Project Overview
DeepForge is an AI project that automatically judges images like a human judge. Instead of a person checking thousands of images manually, DeepForge uses 2 AI models to check if an image is good or not.

This project was built for Hackathon - to solve the problem of slow and biased manual image judging.

**Team Members:**
- Toufeeq Shaik (Original Creator)
- Hema Sri Lakshmi (siri9525) - Documentation
- Jahnavi
- Brundha
- Prathyusha

**GitHub Repo:** https://github.com/siri9525/deepforge

## 🎯 Problem Statement
In many competitions, hackathons, and online platforms, thousands of images are submitted. Checking all images manually takes a lot of time and different judges give different scores. We need a fast, fair, and automatic system.

## 💡 Solution - What is DeepForge?
DeepForge takes an image as input and gives a judgement - Good / Bad, with a score and reason.

It uses 2 Models:
1.  **Model 1 - Quality Check Model:** Checks image quality - blur, lighting, clarity, resolution.
2.  **Model 2 - Content Judgement Model:** Checks content - is it relevant, correct, and meaningful for the topic?

Final Score = Combined result of both models.

## 📊 Dataset
- **Total Images:** 14,000 images
- **Used For:** Training and testing both models
- **Source:** Collected image dataset for image judgement task

## 🛠️ Tech Stack
- Python
- Machine Learning / Deep Learning
- Image Processing Libraries
- GitHub for Version Control

## 📁 Project Structuredeepforge/
├── README.md - Project Documentation
├── Model 1 - Quality Check
├── Model 2 - Content Judgement
├── Dataset - 14,000 Images
└── Results
## 🚀 How To Run This Project (Installation)
1. Clone the repository:
```bash
git clone https://github.com/siri9525/deepforge
cd deepforge
2. install required libraries:
pip install -r requirements.txt
3. Run the model:
python main.py
```
4. Upload your image and see the judgement result.
📈 How It Works - Step by Step
User uploads an image
Model 1 checks Quality - Is image clear or blurry?
Model 2 checks Content - Is image correct for the topic?
DeepForge combines both scores
Final Judgement is shown - Score + Good / Needs Improvement
✅ Results
Trained on 14,000 images
Can judge new images automatically in seconds
Faster than manual judging
More fair and consistent
🔮 Future Scope
Add support for videos
Improve accuracy with more data
Make a web app where anyone can upload and test
Add detailed feedback like "improve lighting"
👥 Authors
Toufeeq Shaik
Hema Sri Lakshmi (siri9525)
Jahnavi
Brundha
Prathyusha
