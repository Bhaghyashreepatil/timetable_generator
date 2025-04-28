# timetable_generator
# Timetable Generator Flask App

This is a simple Flask web application that generates a timetable based on the number of days, slots per day, and a list of subjects. The user inputs these details through a form, and the app will generate a random timetable based on the provided inputs.

## Features

- Input the number of days and slots for your timetable.
- Provide a list of subjects separated by commas.
- Generate a random timetable with subjects assigned to each day and slot.

## Requirements

- Python 3.x
- Flask (Python web framework)

## Setup

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/timetable-generator.git
   cd timetable-generator
2. Create a virtual environment (optional but recommended):


python3 -m venv venv
source venv/bin/activate  # For Windows, use: venv\Scripts\activate
3. Install the required dependencies:


pip install -r requirements.txt
4. Run the Flask app:


python app.py
The app will be available at http://127.0.0.1:5000/.

File Structure
app.py: Main Flask application file.

templates/

index.html: The landing page where the user inputs the number of days, slots, and subjects.

timetable.html: The page where the generated timetable is displayed.

Example
Input:

Days: 5

Slots per day: 3

Subjects: Math, Science, English, History

Output:

A timetable with random subjects assigned to each slot for each day.
