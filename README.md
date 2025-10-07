# Jenkins Declarative Pipeline for Docker Build

This repository demonstrates a simple **Jenkins Declarative Pipeline** that automates building a Docker image.

## 📁 Files
- **Build.bat** – Prints the date and time for the build stage.
- **Dockerfile** – Creates a basic Ubuntu-based Docker image.
- **Jenkinsfile** – Defines the Jenkins pipeline to build and authenticate Docker images.

## 🚀 Steps
1. Jenkins pulls the repository.
2. Builds the Docker image using the Dockerfile.
3. (Optional) Pushes the image to Docker Hub.

## 💡 Example Output
```
Hello world!!! this is my first docker image
```

## 🧰 Tools Used
- Jenkins
- Docker
- Groovy (Declarative Pipeline)
- Windows Batch Script

---
*Simple Jenkins + Docker pipeline project demonstrating CI/CD automation.*
