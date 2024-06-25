# GBCS BE FastAPI Coding Challenge

## Introduction

Welcome to the coding challenge for new software engineer interns at GBCS Group! This challenge is designed to test your ability to work with FastAPI, create endpoints and send POST requests.

## Coding Challenge

### Objective

Your task is to set up a simple FastAPI project, create a POST endpoint, send a POST request and then record a quick video showing a successful request and response while explaining your thought process.

### Steps to Complete the Challenge

1. **Clone the provided repository:**

   ```bash
   git clone -b FastAPI-challenge --single-branch https://github.com/SkyITManagement/coding-challenges.git
   cd coding-challenges/fastapi_challenge
   ```

2. **Set up Virtual Enviorment**
   ```bash
   python -m venv venv
   ```
   On windows:
   ```
   venv\Scripts\activate
   ```
   On MacOS/Linux:
   ```
   source venv/bin/activate
   ```

4. **Install dependencies:**

   ```bash
   pip install fastapi uvicorn
   ```

5. **Run the application:**

   ```bash
   uvicorn main:app --reload
   ```

6. **Navigate to the home page:**
   Open your browser and go to `http://127.0.0.1:8000`, you should see "hello world"

7. **Create Endpoint in main.py and Test:**
   Create a POST endpoint in the “main.py” to receive details about yourself, your name, what you’re studying and what some of your hobbies are. Then you can run the application and test your POST request using any API testing tool of your choice; curl, postman, etc. Feel free to showcase your skills with extra features but only the endpoint is required.

### File to Modify

- `main.py`

## Submission Details

Please follow the instructions below to submit your completed coding challenge:

### Zip the Project:

- Once you have completed the coding challenge, zip the entire project directory.

### Record a Video:

- Record yourself in a short less than 5 minute video explaining your FastAPI project and how you went about creating the endpoint. In the video make sure to include a demonstration that your endpoint is working correctly by sending a POST request and use the endpoint to introduce yourself so that we at GBCS can get to know you. 

### Send Your Submission:

- Email the .zip file of your project and the video to [hr@gbcsgroup.com](mailto:hr@gbcsgroup.com) with the subject line "GBCS Frontend Coding Challenge Submission - [Your Name]".

Thank you for participating in our coding challenge. We look forward to reviewing your submission!
