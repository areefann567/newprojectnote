# Simple Notes App
This is a simple notes app built with React and Django.
<img width="498" alt="Screenshot 2023-12-08 111430" src="https://github.com/areefann567/newprojectnote/assets/120305645/5dbecf59-3da8-4deb-adce-55cc8b51c8d6">


## Requirements
1. Python 3.9
2. Node.js
3. React

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
