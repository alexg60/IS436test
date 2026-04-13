# Docker Deployment with GitHub Actions

This project automates the deployment of an HTML page to Docker Hub using GitHub Actions. Every push to master builds and pushes a new Docker image automatically.

# What is Docker?
Docker packages an application and its dependencies into a container that runs consistently across any environment, eliminating setup and compatibility issues.

# What is GitHub Actions?
GitHub Actions is a CI/CD platform built into GitHub. Here, it automatically builds and pushes a Docker image to Docker Hub on every code push — no manual steps needed.

# How to Run Locally

Pull the image:
docker pull your-dockerhub-username/is436:tagname

Run the container:
docker run -d -p 80:80 --name myapp your-dockerhub-username/is436:tagname

Then open http://localhost:80 in your browser.
