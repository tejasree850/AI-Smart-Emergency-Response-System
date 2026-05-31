# 🚨 Disaster Response Planner

## AI-Based Smart Emergency Response System with Intelligent Routing and Dispatch

An intelligent emergency response platform that leverages Artificial Intelligence, Machine Learning, and Real-World Mapping Technologies to optimize emergency handling processes. The system predicts traffic conditions, estimates emergency severity, assigns appropriate emergency vehicles, and computes optimal routes to reduce response times during critical situations.

---

## 🌟 Project Overview

Traditional emergency response systems often face challenges such as:

- Traffic congestion
- Delayed decision-making
- Inefficient resource allocation
- Static route planning

This project addresses these challenges by integrating:

- Machine Learning-based Severity Prediction
- Traffic Estimation Module
- Intelligent Vehicle Dispatch System
- Real-Time Route Optimization
- Interactive Emergency Response Visualization

The system provides a complete end-to-end workflow for handling medical, fire, and police emergencies.

---

## ✨ Key Features

### 🚑 Smart Emergency Dispatch
Automatically assigns the most suitable emergency vehicle based on:

- Emergency Type
- Predicted Severity Level
- Traffic Conditions

### 🚦 Traffic Estimation
Predicts congestion levels using AI-driven models to simulate real-world traffic conditions.

### ⚠️ Severity Prediction
Evaluates the urgency of incidents and generates a severity score for prioritization.

### 🗺️ Intelligent Route Optimization
Uses OpenStreetMap road networks and shortest-path algorithms to find the fastest route.

### 📍 Real-Time Visualization
Displays:

- Emergency Location
- Destination Facility
- Optimized Route
- Vehicle Movement Simulation

### ⏱ ETA Calculation
Provides estimated arrival times based on route distance and traffic levels.

### 📊 Interactive Dashboard
Shows:

- Traffic Level
- Severity Score
- Assigned Vehicle
- Estimated Time of Arrival (ETA)

---

## 🏗️ System Architecture

```
User Input
     │
     ▼
Location Processing
     │
     ▼
Traffic Estimation
     │
     ▼
Severity Prediction
     │
     ▼
Vehicle Assignment
     │
     ▼
Route Optimization
     │
     ▼
ETA Calculation
     │
     ▼
Map Visualization & Simulation
```

---

## 🛠️ Technologies Used

| Component | Technology |
|------------|------------|
| Programming Language | Python |
| User Interface | Streamlit |
| Machine Learning | Scikit-Learn |
| Deep Learning | TensorFlow |
| Mapping & Routing | OSMnx |
| Graph Algorithms | NetworkX |
| Map Visualization | Folium |
| Geocoding | Geopy (Nominatim) |
| Data Processing | Pandas |
| Numerical Computing | NumPy |

---

## 📂 Project Modules

### 1. Location Processing
- Converts user-entered locations into geographical coordinates.
- Uses Geopy and Nominatim services.

### 2. Traffic Estimation
- Predicts road congestion levels.
- Generates traffic scores between 0 and 100.

### 3. Severity Prediction
- Estimates emergency urgency.
- Produces severity scores for prioritization.

### 4. Intelligent Dispatch
- Selects:
  - Ambulance
  - ICU Ambulance
  - Fire Truck
  - Police Vehicle

### 5. Route Optimization
- Retrieves real-world road networks.
- Computes shortest routes using graph algorithms.

### 6. Visualization & Simulation
- Displays routes on interactive maps.
- Simulates emergency vehicle movement in real time.

---

## 📈 Sample Workflow

1. User enters emergency location.
2. User selects emergency type.
3. System predicts traffic conditions.
4. Severity score is generated.
5. Appropriate emergency vehicle is assigned.
6. Optimal route is computed.
7. ETA is calculated.
8. Interactive map displays the response process.

---

## 🚀 Installation

### Clone the Repository

```bash
git clone https://github.com/yourusername/disaster-response-planner.git
cd disaster-response-planner
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Application

```bash
streamlit run app.py
```

---

## 📸 Application Outputs

The system provides:

- Traffic Prediction
- Severity Analysis
- Emergency Vehicle Assignment
- Route Visualization
- ETA Calculation
- Vehicle Movement Simulation

---

## 🎯 Advantages

- Faster emergency response planning
- Automated decision-making
- Intelligent resource allocation
- Real-world route computation
- Interactive visual dashboard
- Modular and scalable architecture
- Open-source and cost-effective

---

## ⚠️ Current Limitations

- Uses simulated traffic data
- Supports one emergency request at a time
- Fixed destination facility
- Simplified ETA calculations
- Requires internet connectivity
- Not yet integrated with live emergency systems

---

## 🔮 Future Enhancements

- Real-time traffic API integration
- Multiple simultaneous emergency handling
- GPS-based live vehicle tracking
- Dynamic hospital/station selection
- IoT and Smart City integration
- Automatic traffic signal prioritization
- Advanced AI-based dispatch optimization

---

## 👨‍💻 Authors

- Murakonda Kalyani
- Kukkadapu Tejasree
- Ginjala Yamini
- Guntapudi Mohana Krishna
- Rompicherla Lohitha

SRM University AP, India

---


## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.
