# 🐳 Dockerized Portfolio Website

![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white)

This project demonstrates the process of containerizing a simple static portfolio website using Docker.

---

### 🤔 Problem It Solves

In software development, a common issue is the "it works on my machine" problem, where code runs fine on a developer's computer but fails on a server. This project uses Docker to solve that problem by packaging the website code, along with its server environment (Nginx), into a single, portable container.

### 🛠️ Tech Stack

* **Docker:** Used to create a container for the application.
* **Nginx:** A high-performance web server used to serve the static HTML/CSS files from within the container.
* **HTML/CSS:** The core languages for the website itself.

---

### 🚀 How to Run This Project Locally

To see this project running on your own machine, you don't even need to clone this repository! You just need Docker installed.

1.  **Pull the image from Docker Hub:**
    ```bash
    docker pull your-dockerhub-id/portfolio:latest
    ```

2.  **Run the container:**
    ```bash
    docker run -d -p 8080:80 your-dockerhub-id/portfolio:latest
    ```

3.  **Open your browser:**
    Navigate to `http://localhost:8080`, and you will see the website live!

---

### ✅ Key Learnings

This project helped me solidify my understanding of:
* Writing a clean and efficient `Dockerfile`.
* The concept of base images (like Nginx).
* Containerization principles and application packaging.
* Port mapping to access applications running inside a container.
* Pushing and managing images on Docker Hub.
