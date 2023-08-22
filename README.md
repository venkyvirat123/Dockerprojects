# My First Docker Project

This is a simple Django web application Docker project. It demonstrates how to containerize a Django app using Docker and run it in a container.

## Getting Started

To run this project, follow these steps:

1. **Clone the Repository:**

   ```sh
   git clone https://github.com/your-username/my-django-app.git
   cd my-django-app


2. **Build and Run the Docker Image:
Run the following commands to build the Docker image and start a container:
  docker build -t my-django-app .
  docker run -p 4000:8000 my-django-app
3. ** Access the Application:
Open your web browser and navigate to http://localhost:4000/hello/ to see the "Hello, Docker!" message from the Django app.
