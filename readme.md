# AI Workout Planner

This project is an interactive AI-powered Workout Planner web application. It leverages the **RapidAPI AI Workout Planner API** to help users generate workout plans, retrieve exercise details, get personalized nutrition advice, create custom workout routines, and analyze food images for nutritional insights. 

## Features

1. **API Key Management**: Users can input and save their RapidAPI key, which is required for making requests.
2. **Dynamic Tabs**: Tabs allow users to switch between different functionalities seamlessly.
3. **Workout Plan Generator**: Users can generate a personalized workout plan based on fitness goals and preferences.
4. **Exercise Details Retrieval**: This section fetches details about specific exercises, including equipment, muscles worked, and step-by-step instructions.
5. **Nutrition Advice**: Provides a breakdown of daily calories and macronutrients based on user-specific goals, activity levels, and dietary restrictions.
6. **Custom Workout Plan**: Users can create their own workout routines tailored to their preferences and health conditions.
7. **Food Plate Analysis**: Users can analyze food images for nutritional information, balanced meal scores, and dietary insights.
8. **SEO Content**: SEO information is provided for each result to help users understand the content better.

## Getting Started

### Prerequisites

To use this app, you need:
- **RapidAPI Key**: Obtain an API key by subscribing to the API [here](https://rapidapi.com/ltdbilgisam/api/ai-workout-planner-exercise-fitness-nutrition-guide).

### How to Use

1. **Enter API Key**: The API key is required for all functionalities. It can be entered in the top navbar.
2. **Switch Tabs**: Use the tabs to navigate through:
   - **Workout Plan**: Generate a workout plan.
   - **Exercise Details**: Get detailed information on exercises.
   - **Nutrition Advice**: Receive personalized nutrition recommendations.
   - **Custom Plan**: Design a custom workout plan.
   - **Analyze Food**: Analyze an uploaded food image for nutritional information.
3. **Generate Results**: Each tab has a form section where users can enter information relevant to the functionality. Click the **Generate/Submit** button to retrieve the data.

### Structure of the Project

- **Navbar**: Contains the API Key input and a link to obtain a RapidAPI key.
- **Modal**: A welcome modal prompts first-time users to enter their API key.
- **Tabs**: Navigation between different features (Workout Plan, Exercise Details, Nutrition Advice, Custom Plan, Food Analysis).
- **Forms**: Each tab has a corresponding form for data input.
- **Results Section**: Displays results dynamically based on user inputs.
- **Loading Component**: Shows a loading spinner while awaiting API responses.
  
### Key Components

1. **API Key Input**: Saves the API key in local storage.
2. **Workout Plan Form**: Accepts user goals, fitness level, and preferences.
3. **Exercise Details Form**: Takes the exercise name and language to provide specific exercise details.
4. **Nutrition Advice Form**: Based on user weight, goal, and activity level to deliver dietary advice.
5. **Custom Plan Form**: A customizable section where users can set up their fitness plans.
6. **Food Analysis Form**: Allows users to upload or enter a URL for an image, which is then analyzed for nutritional data.

## Acknowledgments

This project utilizes the **AI Workout Planner API** on RapidAPI. For more details, visit the [API documentation](https://rapidapi.com/ltdbilgisam/api/ai-workout-planner-exercise-fitness-nutrition-guide).