# How to perform Pytest tests #
First install the requirements.txt file using the command:

pip install -r requirements.txt

Then run the tests using the command: pytest

The tests can be found in the tests directory

# How to perform checks using OpenAPI #
Ensure the application is running by using the command: uvicorn app.main:app --host 0.0.0.0 --port 8000

Open a browser of your choice and navigate to http://localhost:8000/docs

The Swagger UI lists all available API endpoints along with their descriptions and input parameters. 

You can expand each endpoint to see more details and perform operations such as GET, POST, PUT, and DELETE.

Fill in the required fields and click execute button to send the request to the API endpoint. 
It should work as intended, make sure that once the example account is created.
To log into it by selecting the authorize lock at the top of the page and login with the credentials you used

Afterwards you will be able to make edits to any calculations you've made after the fact.

# Docker Hub Link #
https://hub.docker.com/r/existedmaster/module-13

# ScreenShots #

## Sucessful Login ##
<img width="1407" height="539" alt="image" src="https://github.com/user-attachments/assets/42bdd602-74c5-4f61-ac1f-768de09fd71b" />

## E2E Success ##
<img width="570" height="189" alt="image" src="https://github.com/user-attachments/assets/bd1ffc61-de4a-4e80-bd6f-70d48306985d" />

## Workflow/Actions ##
<img width="1314" height="610" alt="image" src="https://github.com/user-attachments/assets/644750c8-9c5d-46a3-876b-c2ee1131684b" />


