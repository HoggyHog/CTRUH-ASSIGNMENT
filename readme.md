CTRUH ML/AI ASSIGNMENT

This repository contains all the work done for the assignment which comprises of a python script which provides a server backend, and the Web App whose frontend is based on React framework to make use of the Text-To-Image Utility

Steps to install on local machine

1) Download the entire directory into the local machine
2) Install the following dependencies
    Server-side: 
    pip install keras_cv matplotlib numpy pandas tensorflow fastapi PIL uvicorn

    Front end:
    1) Install Node.js installer
    2) npm install -g create-react-app
    3) npm install -D tailwindcss

3) To get the backend running, go to the server folder in the command line, and run this command
uvicorn api:app --reload

Now the server would be hosted on localhost from where we can make api calls using the frontend

4) To get the frontend running on localhost, navigate to WebApp/frontend folder using command line, and run 'npm start', and the user interface would be available on the assigned localhost port

The documentation.txt file contains an explanantion of the server code.