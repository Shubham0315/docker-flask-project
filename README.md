# docker-flask-project

1. Create app.py writing the application need to build

![image](https://github.com/user-attachments/assets/0c0e8db1-357d-4b8b-9178-a7fa86ea93ad)

2. Write requirements to run the app in requirements.txt

![image](https://github.com/user-attachments/assets/7638322d-b67d-4f42-b512-d4791789e51d)

3. Write dockerfile defining base image, setting WORKDIR, installing the requirements dependencies, exposing port and then provide commands to run application written in app.py

![image](https://github.com/user-attachments/assets/17e21ae6-7c03-4241-8779-728399569490)

4. Build docker image :- **docker build -t flask-app .**

![image](https://github.com/user-attachments/assets/2e4fcdd7-5e99-4b9d-9c3b-c1d247d0f1dd)

5. Run container :- **docker run -d -p 5000:5000 flask-app**

![image](https://github.com/user-attachments/assets/dae99350-7c6c-4b34-88c9-8935b0b83475)
![image](https://github.com/user-attachments/assets/01ec0ce2-0a1c-4c46-9a13-8790abb1fbf6)

6. Access application on :- **http://localhost:5000**

![image](https://github.com/user-attachments/assets/4b27de17-9093-484d-925e-37ec7086e9a5)
