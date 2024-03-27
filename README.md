# DevOps Engineer Assignment Submission
## Introduction
Welcome to my submission for the DevOps Engineer assignment. In this repository, you'll find all the necessary files and documentation related to the assignment requirements.

## Assignment Description 
In this assignment I have set up a simple Node/Express REST API that returns a "Hello, World!" response on port 3000. Additionally ,as required I have containerized the application using Docker and for the binus task I have used docker-compose for orchestration.

### Now for steps 1-3 as per the assignment ⬇️
![image](https://github.com/vaibhavmalhotra002/hello-node/assets/76607940/b7c7f311-f4f6-47e8-b1dd-417f1e260ead)

### After running the command: node main.js , i got the API running on http://localhost:3000/
![image](https://github.com/vaibhavmalhotra002/hello-node/assets/76607940/eb9a5cb9-615d-40f2-9efc-cc53537f6fa9)

### Now for Step 5, I created a Dockerfile to build an image for my code 
![image](https://github.com/vaibhavmalhotra002/hello-node/assets/76607940/ec86ff16-1c09-4bc9-b724-53142ce8033b)

### Next use:- docker build -t hello-node-image .
to build docker image 
![image](https://github.com/vaibhavmalhotra002/hello-node/assets/76607940/abaeb716-bb48-440b-b9b5-d499b4c0709a)

### Next use:- docker run -p 3000:3000 hello-node-image
This command maps port 3000 of the container to port 3000 of your localhost. Now we can access our Node.js application at http://localhost:3000 and see the "Hello, World!" response.
![image](https://github.com/vaibhavmalhotra002/hello-node/assets/76607940/eb9a5cb9-615d-40f2-9efc-cc53537f6fa9)

# Bonus Task

## For the Bonus task I have written a docker-compose.yml file which can be found in the repository
**Place it in the root directory of your Node.js project, where your main.js and package.json files are present.

## Run the command:- docker-compose up 
![image](https://github.com/vaibhavmalhotra002/hello-node/assets/76607940/a31538c5-3565-4f8d-bb93-ec89bb86d1b7)

**in the same directory where your docker-compose.yml file is located.





