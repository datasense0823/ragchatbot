MLops Assignment1: Dockerizing the "DataSense Career Guide" Application

Objective: The objective of this assignment is to Dockerize the pre-existing Python application named "DataSense Career Guide", ensuring it runs successfully in a containerized environment.

Assignment Details: What You Need to Do
Dockerize the Application:

You are provided with a Python application (main.py) that launches the "DataSense Career Guide" app.
Your task is to write a Dockerfile to containerize this application.
Environment Configuration:

The application uses a .env file to securely pass environment variables.
You must create a .env file with the following variable:
env
Copy code
GROQ_API_KEY=<your_groq_api_key>
Replace <your_groq_api_key> with your key, which you can get from GROQ API Documentation.
Build and Test:

Build the Docker image and name it datasense-career-guide.
Run the Docker container to ensure the application launches correctly.
Deliverables:

Submit screenshots of:
The Docker image being built successfully.
The Docker container running successfully.
Provide the following files:
Dockerfile
requirements.txt (excluding .env for security reasons)
Instructions
Dockerfile Requirements:

Use a suitable Python base image (e.g., python:3.11-slim).
Copy the application code and .env file into the container.
Install dependencies listed in the requirements.txt.
Specify main.py as the entry point to launch the application.
Image and Container Details:

Name the Docker image: datasense-career-guide.
Expose the necessary ports (e.g., port 8501 if required by the application).
Testing:

Run the container locally to verify the application launches and works correctly.
Capture screenshots during the process:
Building the Docker image.
Running the container with the application.
Submission Guidelines
Deadline: Monday, 19 January, 11:59 PM IST.
Submission Methods:
Email the following to datasense.learning@gmail.com:
Screenshots of the image build and container run.
Dockerfile and requirements.txt.
Alternatively, post your submission on LinkedIn:
Tag Data Sense in your post.
Include the screenshots and a brief explanation of your solution.
