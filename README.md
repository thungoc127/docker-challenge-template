# docker-challenge-template


# Challenge1
1. Creating the "public" folder as the challenge requirement under challenge1 directory
2. Creating the "index.html" File under the "public" directory folder which having my name and my student id.
3. Creating the Dockerfile under challenge1 directory
4. Build the Docker Image using cmd "build -t my-nginx-image" . to create an image from the Dockerfile
5. Create the Docker container using cmd "docker run --name my-nginx-container -d -p 8080:80 my-nginx-image".
6. Test the application to make sure the application by can access the link as "http://localhost:8080" which can display my "index.html" correctly.
7. Screen shot all the terminal and my index page result.

# Challenge2
1. Download challenge2 zip folder from D2L
2. Extracting the challenge2 folder and copy those files into my challenge2 directory.
3. Creating a  Dockerfile in directory and included any necessary code to make it work.
4. Then, creating a docker-compose.yml file which will handle Docker setup.
5. Adding a default.conf file and writing coded settings specific for Nginx server configurations.
6. Run npm install express 
7. Run the cmd docker-compose up --build to build the file.
8. Run localhost:3000/api/books on web browser to get all books infos.
9. Run localhost:3000/api/books/1 on web browser to get 1 books info.
10. Screen shot all the terminal and my api page result.

# Conclusion and Summary
This assignment is really helpful and practical. I studied how to use docker tool to create an containerization which support me a lot in my future work.

DOCKER FINAL ASSIGNMENT
Name: Thu Ngoc Nguyen
Student ID: 000890302

# Challenge 3
1. downloaded challenge3 zip => unzip and save into challenge3 folder
2. Check all  Dockerfile for api, db, nginx folder
3. Create .env file and docker-compose.yml
3. Correct dockerfile and nginx.conf
6.  Run docker-compose up –build
7.Run docker-compose up -d
8.Checking provided urls
9. Screen shot results
9. Run docker-compose ps

# Challenge 4
1. Continue challenge3
2. I made several GET requests to "http://localhost:8080/api/stats" and noted that every response 
3.Run  "docker-compose up -d --scale node-service=3" and I found the error "Docker is trying to bind multiple instances of node-service to the same port (3000) on your host machine"
5. Update "docker-compose.yml" 
6. Run "docker-compose up -d --scale node-service=3"
6. I repeated my GET requests to "http://localhost:8080/api/stats" and observed various hostnames 
7. Run “docker-compose ps"
8.Taking Screenshot and copy to folder

