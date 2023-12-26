# Notes App
created a Jenkins CI/CD pipeline for a Dockerized web application, optimizing development and deployment.
<img width="498" alt="Screenshot 2023-12-08 111430" src="https://github.com/areefann567/newprojectnote/assets/120305645/5dbecf59-3da8-4deb-adce-55cc8b51c8d6">


## Requirements
1. Python 3.9
2. Node.js
   

## Installation
1. Clone the repository
```
https://github.com/areefann567/newprojectnote.git
```

2. Build the app
```
docker build -t notes-app .
```

3. Run the app
```
docker run -d -p 8000:8000 notes-app:latest
```

## Nginx

Install Nginx reverse proxy to make this application available

`sudo apt-get update`
`sudo apt install nginx`
![image](https://github.com/areefann567/newprojectnote/assets/120305645/f121a5c4-f761-4f30-b724-75cb1ad682df)

![image](https://github.com/areefann567/newprojectnote/assets/120305645/1aa9b507-f546-4502-bfc2-5d141b4f97af)
