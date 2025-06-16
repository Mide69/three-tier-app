# three-tier-app
Full-stack three-tier Node.js application with Docker: Frontend, Backend API, and MongoDB database. Fully containerized and ready for local development or cloud deployment.

# Three-Tier Node.js Application (Frontend, Backend, MongoDB)

This project demonstrates a full-stack Node.js application structured into three tiers:

- Frontend: React (or your preferred framework)
- Backend: Node.js / Express API
- Database: MongoDB

All components are fully containerized using Docker and orchestrated with Docker Compose for seamless local development and deployment.

---

## 🗂 Project Structure
├── frontend/ # React/Vue frontend
├── backend/ # Node.js/Express backend
├── mongo-data/ # Persistent MongoDB data
├── docker-compose.yml
└── README.md

# Build all images
docker-compose build

# Start the full stack
docker-compose up

Access:

Frontend: http://localhost:3000

Backend API: http://localhost:5000

MongoDB: accessible internally at mongo:27017

cd frontend
docker build -t your-dockerhub-username/frontend:latest .
docker push your-dockerhub-username/frontend:latest

cd frontend
docker build -t your-dockerhub-username/frontend:latest .
docker push your-dockerhub-username/frontend:latest

cd backend
docker build -t your-dockerhub-username/backend:latest .
docker push your-dockerhub-username/backend:latest

docker pull mongo:latest

git clone https://github.com/yourusername/three-tier-nodeapp.git
cd three-tier-nodeapp

docker-compose pull
docker-compose up -d


![Screenshot (62)](https://github.com/user-attachments/assets/a7e5d9a1-3c27-41a5-bf8b-463c1647e3ab)
![Screenshot (61)](https://github.com/user-attachments/assets/0e0a72ce-74db-450d-bd65-cba2c43db2f1)
![Screenshot (60)](https://github.com/user-attachments/assets/f886f30c-ec94-46d8-bc65-bf5c7656f31f)






