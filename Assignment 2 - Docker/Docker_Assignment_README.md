# Docker Assignments

## Objective
This project demonstrates containerization using Docker, including pulling images, running containers, configuring Apache2, publishing images to Docker Hub, and building custom Dockerfiles with HTML content.

---

## Tasks Completed

### A. Basic Docker Container
- Pulled an **Ubuntu container**.  
- Ran the container and mapped **port 80** to the local machine.  
- Installed **Apache2** inside the container.  
- Verified access to the Apache page in the browser.  

---

### B. Save and Launch Custom Image
- Saved the configured container as a **custom Docker image**.  
- Launched a new container from this image and mapped it to **port 81**.  
- Started the Apache2 service inside the container.  
- Verified browser access on the mapped port.  

---

### C. Docker Hub Deployment
- Reused the saved image from the previous step.  
- Uploaded the image to **Docker Hub**.  
- Pulled the image on another machine and launched it on **port 80**.  
- Started the Apache2 service and verified browser access.  

---

### D. Dockerfile Creation
- Created a **Dockerfile** with the following specs:  
  - Base image: Ubuntu  
  - Installed Apache2  
  - Configured Apache2 to start automatically when the container runs.  

---

### E. Custom HTML Page
- Created a **sample HTML file**.  
- Used the Dockerfile from the previous step.  
- Replaced the default Apache2 index page with the custom HTML file inside the container.  
- Verified browser access to the custom HTML page.  

---

## Docker Concepts Demonstrated
- Pulling and running containers  
- Port mapping  
- Installing services inside containers  
- Saving and reusing Docker images  
- Publishing to Docker Hub  
- Writing Dockerfiles  
- Deploying static web content in containers  

---

## Outcome
Successfully demonstrated Docker fundamentals, from basic container usage to creating custom Docker images and deploying them via Docker Hub, enabling a reproducible and portable containerized web server environment.  
