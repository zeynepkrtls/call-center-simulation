# Call Center Simulation – AnyLogic Project

This repository contains a discrete event simulation model of a **Call Center** designed using **AnyLogic**.

## 📌 Project Overview

The simulation reflects a realistic call center scenario, optimizing both human and automated operator resources under high call volume. It explores how call routing and operator availability affect customer satisfaction and overall performance.

### Key Features:
- 📞 **100 incoming calls per minute** modeled using a call source.
- 👩‍💼👾 Callers are routed **randomly (50/50)** to either:
  - A **human operator** (150 agents, each handling one call at a time), or  
  - An **automated robot operator** (1 robot serving up to 150 callers simultaneously).
- 🔁 50% of callers who first chose a robot chose to switch to a human agent.
- ⏳ If a caller does not reach an operator within an exponential timeout (mean: 1/802), the call is dropped.
- 📊 Visualization:
  - A **pie chart** showing answered vs. unanswered calls.
  - A **histogram** displaying call duration distribution (2 to 6 minutes).
  
### 🛠 Technologies & Tools
- AnyLogic Simulation Software
- Process Modeling with Resource Pools
- Delay and Capacity Management
- Real-world inspired stochastic behavior

## 💡 Purpose
To simulate the operational flow of a call center in a **cost-effective** and **realistically complex environment**, allowing for performance optimization, resource planning, and analysis of customer behavior under varying load conditions.

## 📁 Files
- `callCenter.alp`: The main AnyLogic project file.

---


