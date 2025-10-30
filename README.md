## 🎯 Practice Objectives
      Containerize a Flask application using Docker - Package the Python Flask app into a portable container that runs anywhere

    Implement health check endpoints - Create /health endpoint to monitor if application is running properly

   Practice Git workflow and documentation - Use Git commands and create proper project documentation

  Create reusable Docker images - Build Docker images that can be deployed on any system

## 🏃‍♂️ Quick Start
```bash

## Build and run

### Create a container image
docker build -t dice_app .

### Start the application on port 5000
docker run -p 5000:5000 dice_app

http://localhost:5000 - Main application

http://localhost:5000/health - Health check page

http://localhost:5000/roll/20 - Roll a 20-sided dice