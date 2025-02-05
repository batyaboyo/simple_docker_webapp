# simple_docker_webapp
A simple Web App showing Docker implementation using python flask


### Instructions to Use the Repository

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/batyaboyo/simple-docker-webapp.git
   cd simple-docker-webapp
   ```

2. **Build the Docker Image**:

   ```bash
   docker build -t simple-docker-app .
   ```

3. **Run the Docker Container**:

   ```bash
   docker run -p 5070:5070 simple-docker-webapp
   ```

4. **Visit the Application**:

   Open your web browser and go to `http://localhost:5070` to see the application running.

