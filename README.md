# NutriBot - AI-Powered Nutrition Assistant

## Overview
NutriBot is an intelligent web application that helps users manage their nutrition, track weight goals, and discover recipes using AI. Built with Flask and OpenAI's GPT models, it provides personalized health recommendations based on user profiles and pantry ingredients.

## Key Features

### Smart Chatbot
- AI-powered nutrition advice using GPT-3.5-turbo
- Personalized recommendations based on user health profile
- Natural conversation interface for health-related queries

### Food Image Detection
- Upload photos of food items
- AI automatically detects ingredients using GPT-4 Vision
- Automatically adds detected items to your virtual pantry

### Recipe Generator
- Generates recipes based on your available pantry ingredients
- Customizable recipe count and dietary preferences
- Smart ingredient combination detection

### Weight Journey Tracking
- Log daily weight entries
- Visual progress charts using Chart.js
- Set weight loss/gain goals
- Achievement milestones system
- BMI calculation and tracking

### User Profile System
- Secure login/signup system
- Store age, height, weight, gender
- Automatic BMI and daily calorie calculations
- Edit health information anytime

## Tech Stack

| Category | Technologies |
|----------|-------------|
| Backend | Flask 3.0.2, Python |
| AI/ML | OpenAI API (GPT-3.5-turbo, GPT-4 Vision) |
| Data Processing | NLTK, NumPy, SciPy |
| Frontend | HTML5, Bootstrap 5, JavaScript |
| Charts | Chart.js |
| Database | JSON file-based storage |
| Authentication | Session-based with Flask |

## Installation

```bash
# Clone repository
git clone https://github.com/yourusername/nutribot.git
cd nutribot

# Install dependencies
pip install -r requirements.txt

# Create .env file with your OpenAI API key
echo "OPENAI_API_KEY=your_key_here" > .env

# Run the application
python server.py
