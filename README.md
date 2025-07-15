# contact-app-aws-node1
contact app using MySQL,Docker , and AWS Free Tier
git init
git remote add origin 
https: //github.com/Ashwinishukla02/contact-app-aws-node1.git
git add .
git commit -m " Initial commit -AWS Contact App"
git push -u origin master
# 📇 Contact App – Node.js + MySQL + Docker + AWS

A full-stack Contact App hosted completely on *AWS Free Tier*.  
Built using:
- MySQL (Amazon RDS)
- Docker (on EC2)

## 🧱 Tech Stack
- Node.js + Express backend
- MySQL database (RDS)
- Dockerized deployment
- Hosted on Amazon EC2

---

## 📸 Screenshots

| App UI | Free Tier Proof |
|--------|-----------------|
 Free Tier(free-tier-proof.jpg) 
 
## ✅ AWS Free Tier Confirmation

All services used in this project are within AWS Free Tier limits:
- EC2: t2.micro (750 hrs/month)
- RDS: db.t2.micro (750 hrs/month)
- No paid resources used.
- 
## 🧠 What I Learned
- Connecting EC2 and RDS
- Fixing port conflicts & timeouts
- Real-world AWS debugging

---

## 📂 How to Run It Yourself
```bash
 Run Docker container
docker run -p 80:3000 \
  -e DB_HOST="docker run --rm -p 80:3000 -e DB_HOST="database-1.ckt8ggoiizz8.us-east-1.rds.amazonaws.com" -e DB_USER="admin" -e DB_PASSWORD="ashwini123" -d philippaul/node-mysql-app:02" \
  -e DB_USER="admin" \
  -e DB_PASSWORD="ashwini123" \
  philippaul/node-mysql-app:02
