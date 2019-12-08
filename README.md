# DockerStaticWebApp :tada:

***Steps to Run the app***
1. Clone the repository.
2. Make Sure you have installed Docker in your machine and Running Awesome!
3. Go to /Particle Folder
4. We will find 
      1. Dockerfile
      2. index.html
      3. Particle.js
      4. favicon_io folder

Lets deep dive into Docker File

Dockerfile

```
FROM nginx:alpine
COPY . /usr/share/nginx/html
```

- 1st Line - Every Docker Image should have an Base image, since we are going to display a static web page, we use nginx and alpine
- 2nd Line - We are copying the current directory's content (I mean 4.1, 4.2, 4.3, 4.4) to /usr/share/nginx/html inside the container's file system.

Thanks
