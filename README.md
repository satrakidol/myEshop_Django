# E-Commerce Backend Platform (Django)

A modular e-commerce backend platform built with Django 5.2.5 and containerized using Docker.

## 🚀 How to Run with Docker

1. Make sure you have **Docker Desktop** installed and running on your machine.
2. Open your terminal or command prompt in the project root directory.
3. Build and launch the application environment by running:
   ```bash
   docker compose up --build
   ```

## 🌐 How to Access the Application

Once the Docker build is complete, the Django container will start listening for requests. 

* **Important Note:** The terminal logs will display `Starting development server at http://0.0.0`. Because the server is running inside an isolated Docker container network, **do not click the 0.0.0.0 link directly**.
* To view and interact with the live application, open your web browser and navigate manually to:

👉 **[http://127.0.0.1:8000/products/](http://127.0.0.1:8000/products/)** or **[http://localhost:8000/products/](http://localhost:8000/products/)**

## 🛑 How to Stop the Server
To safely stop and spin down the running container environments, press `CTRL + C` inside your terminal window.