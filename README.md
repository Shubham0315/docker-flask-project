# docker-flask-project

1. Create app.py writing the application need to build

2. Write requirements to run the app in requirements.txt

3. Write dockerfile defining base image, setting WORKDIR, installing the requirements dependencies, exposing port and then provide commands to run application written in app.py

4. Build docker image :- **docker build -t flask-app .**

5. Run container :- **docker run -d -p 5000:5000 flask-app**

6. Access application on :- **http://localhost:5000**
