# 🔐 Phishing Simulation Project (Kubernetes)

## 📌 Overview
This project simulates a phishing login system deployed on Kubernetes.  
It captures user credentials through a frontend interface, processes them via a backend API, and stores them securely in a MySQL database.

---

## Architecture
Frontend (Nginx) → Backend (Flask API) → MySQL Database

---

## Tech Stack
- Kubernetes (Minikube)
- Docker
- Nginx (Frontend)
- Python Flask (Backend)
- MySQL (Database)

---

##  Features
-  RBAC (Role & RoleBinding)
-  Persistent Storage (PV & PVC)
-  Init Container to fetch frontend from GitHub
-  Ingress-based routing
-  Full end-to-end data flow (Frontend → Backend → DB)

---

## 📂 Project Structure

│
├── frontend/
├── backend/
├── k8s/
│ ├── frontend-deployment.yaml
│ ├── backend-deployment.yaml
│ ├── db-deployment.yaml
│ ├── services.yaml
│ ├── ingress.yaml
│ ├── role.yaml
│ ├── rolebinding.yaml
│ ├── pv.yaml
│ ├── pvc.yaml

##  Deployment

Apply all Kubernetes configurations:

```bash
kubectl apply -f k8s/

## Author
Khadijah JamalEldean 
