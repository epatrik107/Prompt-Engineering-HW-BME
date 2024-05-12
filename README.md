# Personalized Workout Plan Generator

This project is a Python-based web application that generates personalized workout plans. It uses Flask as the web framework and OpenAI's API to generate the workout plans based on user inputs.

## Features

- Users can specify their fitness goal (weight loss or muscle gain), the number of weeks they want the plan to last, and the location where they will be working out.
- The application sends this information to the OpenAI API, which generates a detailed workout plan.
- The plan is then formatted and displayed to the user.

## Setup

1. Clone the repository.
2. Install the required dependencies using pipenv:

```bash
pip install pipenv
pipenv install
```

3. Set up the environment variables in a `.env` file:

```dotenv
OPENAI_API_KEY=your_openai_api_key
ASSISTANT_ID=your_assistant_id
THREAD_ID=your_thread_id
```

4. Run the application:

```bash
python main.py
```

## Usage

Navigate to the application in your web browser. Fill in your fitness goal, the number of weeks, and the location. Click on the "Generate" button to get your personalized workout plan.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
