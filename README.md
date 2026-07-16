# ☁️ IdlePod – Intelligent Idle Container Detection & Energy-Efficient Resource Optimization

IdlePod is an intelligent cloud-native optimization platform that detects idle Kubernetes pods, validates them using machine learning, and safely optimizes cluster resources. The platform combines adaptive thresholding, heuristic scoring, Isolation Forest validation, and AWS cloud services to reduce cloud costs, energy consumption, and resource waste while ensuring cluster stability.

---

## 🚀 Features

- Intelligent idle pod detection using multiple resource metrics
- Adaptive thresholds instead of fixed CPU utilization rules
- Heuristic confidence scoring for explainable optimization decisions
- Isolation Forest machine learning validation
- Safe workload optimization with namespace protection
- Real-time Kubernetes monitoring dashboard
- Energy consumption and CO₂ savings analytics
- Cloud cost estimation
- JWT-secured REST APIs
- AWS cloud integration for monitoring, alerting, and automation

---

# 🏗️ System Architecture

```
React Dashboard
       │
       ▼
 FastAPI Backend
       │
 ┌───────────────┐
 │ Detection Engine │
 ├───────────────┤
 │ Adaptive Thresholds │
 │ Heuristic Scoring   │
 │ Isolation Forest ML │
 └───────────────┘
       │
       ▼
 Kubernetes Cluster
       │
       ▼
 Optimization Engine
       │
       ▼
 AWS Services
(SNS • S3 • CloudWatch • Lambda • EC2)
```

---

# ✨ Key Features

- Multi-signal idle workload detection
- CPU, Memory, Network, Uptime and Request monitoring
- Adaptive threshold engine
- Explainable heuristic scoring
- Isolation Forest anomaly detection
- Automatic optimization recommendations
- Namespace exclusion for cluster safety
- Cloud cost tracking
- Energy and carbon footprint estimation
- Real-time monitoring dashboard

---

# 🛠 Tech Stack

## Frontend

- React
- React Router
- Axios
- Chart.js
- Docker
- Nginx

## Backend

- Python
- FastAPI
- JWT Authentication
- REST APIs

## Machine Learning

- Scikit-learn
- Isolation Forest
- NumPy
- Pandas

## Infrastructure

- Kubernetes
- Minikube
- Docker
- Docker Compose
- Metrics Server
- Kubernetes Python Client

## AWS Services

- Amazon SNS
- Amazon S3
- Amazon CloudWatch
- CloudWatch Alarms
- AWS Lambda
- IAM
- Amazon EC2
- AWS Cost Explorer

## Database

- MongoDB Atlas
- SQLite (Fallback)

---

# 📂 Project Structure

```
IdlePod/

├── frontend/
│   ├── src/
│   ├── public/
│   └── Dockerfile
│
├── backend/
│   ├── api/
│   ├── optimizer/
│   ├── ml/
│   ├── auth/
│   ├── database/
│   └── Dockerfile
│
├── kubernetes/
│   ├── manifests/
│   └── rbac/
│
├── aws/
│   ├── lambda/
│   ├── cloudwatch/
│   └── sns/
│
├── docker-compose.yml
├── requirements.txt
└── README.md
```

---

# ⚙️ How It Works

1. Collect Kubernetes pod metrics.
2. Calculate adaptive CPU and memory thresholds.
3. Generate heuristic idle confidence scores.
4. Validate idle pods using Isolation Forest.
5. Exclude protected Kubernetes namespaces.
6. Optimize eligible workloads.
7. Send alerts through Amazon SNS.
8. Store optimization reports in Amazon S3.
9. Publish metrics to CloudWatch.
10. Display analytics on the React dashboard.

---

# ☁️ AWS Integration

| Service | Purpose |
|----------|---------|
| Amazon SNS | Email notifications |
| Amazon S3 | Store reports and logs |
| CloudWatch | Monitoring and custom metrics |
| CloudWatch Alarm | Alert triggering |
| AWS Lambda | Automation workflows |
| IAM | Secure permissions |
| EC2 | Cloud deployment |
| Cost Explorer | Cloud cost analytics |

---

# 📊 Dashboard

The React dashboard provides:

- Live Kubernetes pod monitoring
- Idle confidence scores
- ML validation results
- Optimization history
- Cluster efficiency metrics
- AWS integration status
- Cost savings
- Energy savings
- CO₂ reduction analytics

---

# 🔒 Security

- JWT Authentication
- Kubernetes RBAC
- Namespace protection
- Secure REST APIs
- Protected optimization actions

---

# 📈 Results

IdlePod helps organizations by:

- Reducing cloud infrastructure costs
- Improving Kubernetes resource utilization
- Lowering energy consumption
- Reducing carbon emissions
- Preventing unsafe optimization of critical workloads
- Providing explainable AI-assisted optimization

---

# 🔮 Future Enhancements

- Amazon EKS deployment
- Multi-cluster support
- Predictive idle detection using LSTM
- KEDA integration
- Amazon Bedrock AI recommendations
- Carbon accounting APIs
- Horizontal scaling
- Advanced analytics dashboard

---

# 🎯 Learning Outcomes

This project demonstrates practical implementation of:

- Kubernetes
- Cloud Computing
- AWS Services
- FastAPI
- React
- Docker
- Machine Learning
- Distributed Systems
- Resource Optimization
- Cloud Cost Optimization
- Sustainable Computing

---

# 👨‍💻 Author

M.Sai Meghana


---

## ⭐ If you found this project useful, consider giving it a star!
