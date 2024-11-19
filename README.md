# weather-dashboard-project
Real-Time Weather Dashboard 🌦️
A Dockerized web application to fetch and display real-time weather information for cities around the world.

This project is a distributed application built with microservices, leveraging Python, React, Redis, and Celery for seamless weather data retrieval and display. It demonstrates the use of containerized services with Docker, message queues, and a modern front-end interface.

Features
Real-Time Weather Updates: Fetch weather data for any city using the OpenWeatherMap API.
Interactive UI: React.js-powered frontend for easy user interaction.
Scalable Backend: Python-based Flask API for serving weather data.
Background Processing: Celery worker to handle asynchronous tasks for fetching weather data.
Redis Integration: In-memory caching to store weather data and reduce API calls.
Dockerized Setup: Easy deployment with Docker Compose for seamless multi-container orchestration.
Architecture
The application consists of the following components:

Frontend: React.js application served on http://localhost:3000.
Backend: Flask API for fetching and serving weather data.
Worker: Celery task worker for retrieving weather data from the OpenWeatherMap API.
Redis: In-memory database for caching weather information.
Technologies Used
Frontend: React.js
Backend: Python (Flask)
Worker: Celery + Redis
Caching: Redis
Containerization: Docker, Docker Compose
How to Use
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/weather-dashboard.git
cd weather-dashboard
Run the application with Docker Compose:

bash
Copy code
docker-compose up --build
Access the application:

Frontend: http://localhost:3000
Backend API: http://localhost:5000/weather?city=London
Contributing
Contributions are welcome! Feel free to submit issues or pull requests to improve the project.

License
This project is licensed under the MIT License.
