# Personalized Diet Planner

This Streamlit application provides personalized diet plans based on user inputs like budget, age, height, weight, and dietary restrictions. It leverages the power of OpenAI's GPT models to generate a weekly diet plan tailored to individual needs and preferences.

## Features

- **User Input**: Enter budget, age, height, weight, and dietary restrictions.
- **Integration with OpenAI GPT-3.5-turbo**: Uses advanced AI to create personalized diet plans.
- **Weekly Diet Plan**: Generates a diet plan in a markdown table format including day, meals, cost, and calories.

## Installation

To run this application, you need to install the required Python libraries. 

1. Clone this repository:
   ```
   git clone [repository URL]
   ```
2. Install the requirements:
   ```
   pip install -r requirements.txt
   ```

## Usage

Before running the application, ensure you have an OpenAI API key set up.

1. Set up your OpenAI API key (replace `YOUR_API_KEY` with your actual key):
   ```python
   openai.api_key = 'YOUR_API_KEY'
   ```
2. Run the Streamlit application:
   ```
   streamlit run app.py
   ```

3. Open your web browser and go to `http://localhost:8501`.
