# Node.js + MongoDB with Docker Compose

A simple Dockerized Node.js application connected to a MongoDB database, orchestrated using Docker Compose.

## 📌 Features

- Node.js Express backend API
- MongoDB database with persistent volume
- Easy development setup using Docker Compose
- Sample REST API (customize as per your project)

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository
```bash
git clone git@github.com:sukrutgangurde/node-mongo-docker-compose.git
cd node-mongo-docker-compose


steps to run
first cd at backend and run command npm install for node_modules

after that cd .. to main directory
then run docker-compose up --build -d 

in security groups of ec2 instance edit inboud rule and allow port 3000 
 after that  :-  Access the App
Backend API: http://localhost:3000

MongoDB: Accessible within Docker network at mongo:27017


🗂️ Project Structure
node-mongo-docker-compose/
├── backend/            # Node.js backend
│   ├── Dockerfile
│   ├── package.json
│   └── src/
│       └── index.js    # Main Express app
├── docker-compose.yml  # Docker Compose configuration
└── README.md           # Project documentation



✉️ Contact
Maintained by Sukrut Gangurde
📧 sukrutgangurde@gmail.com
GitHub: sukrutgangurde
