# 🚗 Autonomous Parking Lot Simulator

## 📌 Overview

This project is a full-stack **Autonomous Parking Lot Simulator** that models and solves the **Multi-Agent Path Finding (MAPF)** problem in a dynamic parking environment.

The system simulates autonomous vehicles entering, navigating, and parking while avoiding collisions and optimizing movement. It includes both **2D and 3D visualizations**, along with tools for designing parking layouts and analyzing simulation performance.

---

## 🧠 Core Concepts

* **Multi-Agent Path Finding (MAPF):**
  Planning collision-free paths for multiple agents in a shared space

* **Autonomous Navigation:**
  Vehicles dynamically compute paths while considering other agents

* **Simulation & Analytics:**
  Evaluate system performance using metrics such as wait time and throughput

---

## 🚀 Features

### 🅿️ Parking Simulation Engine

* Real-time simulation of vehicle movement
* Collision avoidance and path coordination
* Dynamic scheduling of incoming vehicles

---

### 🧭 Path Planning (MAPF)

* Priority-based planning approach
* Reservation table for conflict prevention
* Configurable planning horizon

---

### 🧱 Parking Lot Generator

* Automatically generate parking layouts
* Configurable size and structure
* Supports roads, parking slots, entrances, and exits

---

### ✏️ Parking Lot Editor

* Interactive editing of parking layouts
* Place and modify:

  * Roads
  * Parking spots
  * Entry/exit points
  * Obstacles

---

### 📊 Simulation Analytics

* Track key performance metrics:

  * Average wait time
  * Throughput
  * System efficiency
* Compare results across multiple simulation runs

---

### 🎮 2D & 3D Visualization

* **2D View:** Grid-based simulation for clarity and debugging
* **3D View:** Interactive visualization of vehicle movement

---

## 🏗️ Architecture

### Backend

* **Python**
* Simulation engine
* MAPF planning algorithms
* Parking lot generation

### Frontend

* **React (Vite / TypeScript)**
* Simulation UI
* Editor interface
* 2D & 3D rendering

---

## 📁 Project Structure

```
Final_Project_Group_N/
│
├── backend/
│   ├── core/              # Simulation engine
│   ├── planning/          # MAPF algorithms
│   ├── generator/         # Parking lot generator
│
├── frontend/
│   ├── src/
│   │   ├── pages/         # Simulation & editor views
│   │   ├── components/    # UI components
│
├── README.md
```

---

## ▶️ Project Activation Instructions

### 📦 Prerequisites

Make sure the following are installed:

* Node.js
* Python (3.10+ recommended)

---

## 🚀 Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

Frontend runs on:

```
http://localhost:5173
```

---

## 🧠 Backend Setup

```bash
cd backend
```

### Create and activate virtual environment

```bash
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

### Install dependencies

```bash
pip install fastapi uvicorn sqlalchemy
```

or:

```bash
pip install -r requirements.txt
```

### Run the server

```bash
uvicorn api_app:app --reload
```

Backend runs on:

```
http://127.0.0.1:8000
```

API documentation:

```
http://127.0.0.1:8000/docs
```

---

## 🧪 Usage

1. Generate or design a parking lot
2. Configure simulation parameters
3. Run the simulation
4. Observe vehicle behavior in 2D/3D
5. Analyze performance metrics

---

## 🎯 Goals

* Demonstrate application of **MAPF algorithms**
* Build a **full-stack simulation system**
* Explore optimization in constrained environments
* Provide intuitive visualization tools

---

## 💡 Future Improvements

* Advanced MAPF algorithms (CBS, M*)
* Real-time adaptive replanning
* Improved UI/UX
* Scalability for large environments

---

## 📄 License

This project is for academic and educational purposes.
