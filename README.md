# Chatter

Chatter is a simple chat application that allows users to chat with each other in real-time. It is built using React and Flask.


Tutorial: [Build the best Chat App with Python, JavaScript & Chat Engine](https://blog.chatengine.io/fullstack-chat/python-javascript)

## Setup

1. Create a empty directory and navigate to it.
2. Clone the repository: `git clone https://github.com/alamorre/js-chat-website.git frontend`
3. Navigate to the frontend directory: `cd frontend`
4. Install the dependencies: `npm install` and run the application: `npm run dev`
5. Open a new terminal and navigate to the root directory of the project.
6. Create backend directory: `mkdir backend` and `cd backend`.
7. Create a virtual environment: `python -m venv venv`(Windows) and activate it: `source venv/Scripts/activate`(Windows) or `source venv/bin/activate`(Mac/Linux).
8. Install the dependencies: `pip install fastapi "uvicorn[standard]" requests`.
9. Run the backend server: `uvicorn main:app --reload --port 3001`.