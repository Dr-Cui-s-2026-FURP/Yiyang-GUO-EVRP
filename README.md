# 🚁🚗 VRP Problem Combining UAVs and Autonomous Vehicles  
*Hybrid logistics optimization system for coordinated aerial/ground last-mile delivery*

## 🎯 Project Description  
This project investigates a **multi-modal Vehicle Routing Problem (VRP)** system integrating autonomous delivery vans and UAVs. Key innovations include:  
- 🧠 Cooperative routing algorithms for truck-drone tandem operations  
- 🔋 Joint energy-time optimization framework  
- 🌐 Dynamic re-planning for urban traffic constraints  
- 📦 Cargo handover synchronization mechanics  

The system aims to:  
1. Reduce last-mile delivery costs by 30-40%  
2. Improve delivery time reliability in dense urban areas  
3. Enable adaptive fleet coordination through digital twin simulation  

## 🔧 Skill Requirements  
### Core Competencies  
- **Optimization Methods**: MILP formulation, Metaheuristics (ALNS/GA)  
- **Programming**: Python (OR-Tools, PuLP), ROS navigation stack  
- **GIS Knowledge**: OSMnx for urban network analysis  
- **Robotics**: Basic UAV/UGV control understanding  

### Specialized Skills  
- 📈 Experience with VRP variants (VRPTW, HVRP)  
- ⚡ Power consumption modeling (UAV batteries)  
- 🚦 Urban traffic pattern analysis (SUMO simulation)  
- 🤖 Multi-agent system coordination  

## 🗓️ Milestones  
| Week | Phase | Objectives |  
|------|-------|------------|  
| 1-3  | 🧮 **Problem Modeling** | Develop energy-aware MILP formulation |  
| 4-6  | 🧬 **Algorithm Design** | Create hybrid ALNS-GA solver |  
| 7-9  | 🖥️ **Simulation Setup** | Build digital twin with SUMO+AirSim |  
| 10-12| ⚡ **Real-World Integration** | Implement ROS-based fleet coordination |  
| 13-14| 📊 **Validation** | Benchmark against Amazon Last-Mile routes |  

## 📋 Work Breakdown Structure  
### Phase 1: System Modeling  
1. Formulate time-energy joint cost function  
2. Model UAV range constraints with wind effects  
3. Develop truck-drone handover time matrix  

### Phase 2: Optimization Engine  
1. Implement adaptive large neighborhood search (ALNS)  
2. Create genetic algorithm with domain-specific operators  
3. Develop failure recovery sub-module  

### Phase 3: Simulation Environment  
1. Build urban digital twin with delivery hotspots  
2. Implement traffic-aware UAV corridor generation  
3. Create dynamic obstacle avoidance rules  

### Phase 4: Hardware Integration  
1. Develop ROS package for DJI Matrice ↔ TurtleBot3 comms  
2. Implement visual servoing for package handoff  
3. Create safety protocol for urban drone operations  

### Phase 5: Performance Analysis  
1. Define Key Performance Indicators (KPIs):  
   - Energy-per-parcel  
   - Temporal reliability index  
   - Handover success rate  
2. Conduct sensitivity analysis on fleet size ratios  

## 🚀 Deliverables  
- Open-source hybrid VRP solver "HVRP-Connect"  
- ROS 2 package for coordinated navigation  
- Digital twin simulation toolkit  
- Industrial partnership white paper  
- Physical demonstration with 3 drones + 1 AV  

## ⏳ Time Commitment  
- 14-16 hrs/week (includes lab equipment access)  
- Weekly optimization challenges  
- Mid-term simulation hackathon  
- Final industry review panel  

💡 *Theoretical Focus Areas:*  
- Mixed integer nonlinear programming  
- Swarm intelligence for fleet coordination  
- Regulatory-compliant UAV routing  

🛠️ *Hardware Stack:*  
- DJI Enterprise Drones with SDK  
- NVIDIA Jetson-based AV platform  
- Mock urban testbed with RFID drop points  

This framework emphasizes:  
1) Joint optimization of aerial/ground assets  
2) Energy-logistics co-optimization  
3) Cyber-physical system validation  
4) Scalability for commercial adoption  

## Workload:
### Week1: To understand VRP problems, try out the https://pyvrp.org/ toolkit and the Ai4co.org toolkit on your local machine.
### Dateset: CVRPLib http://vrp.galgos.inf.puc-rio.br/index.php/en/
