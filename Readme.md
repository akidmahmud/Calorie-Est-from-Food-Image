# Food Nutrition Analyzer 🍽️

AI-powered food image analysis app that identifies meals from photos and returns detailed nutritional breakdowns with personalized dietary recommendations. Built with Streamlit and Google Gemini API.

**Live Demo:** [Food Nutrition Analyzer](https://count-foodnutrition-by-foodimagegit-mwgvpe9juwtw3xvgwaiept.streamlit.app/)

## Features

- **Image-Based Food Recognition** — Upload a photo of any meal and get instant AI-powered identification using Google Gemini.
- **Macro & Micronutrient Breakdown** — View calories, protein, carbs, fat, vitamins, and minerals in organized tabs.
- **Dietary Goal Suggestions** — Select your goal (weight loss, muscle gain, maintenance) and receive tailored improvement tips.
- **Meal History** — All analyzed meals are stored locally via SQLite for tracking and reference.

## How It Works

1. Upload a food image (JPG, PNG).
2. Select your dietary goal from the dropdown.
3. Click **Analyze Image**.
4. View results across three tabs: Macronutrients, Micronutrients, and Suggestions.

## Tech Stack

| Layer         | Technology              |
|---------------|-------------------------|
| Frontend/UI   | Streamlit 1.29          |
| AI/Vision     | Google Gemini API       |
| Database      | SQLite                  |
| Language      | Python 3.9              |

## Local Setup

```bash
git clone https://github.com/akidmahmud/Count-FoodNutrition-by-FoodImage.git
cd Count-FoodNutrition-by-FoodImage
pip install -r requirements.txt
```

Create a `.env` file and add your Gemini API key:
