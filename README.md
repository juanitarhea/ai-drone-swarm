# AI Drone Swarm for Disaster Relief
University of KwaZulu-Natal | 2026

Five AI models forming a drone swarm system for disaster relief:

| Model | Name | Purpose | Method |
|-------|------|---------|--------|
| M1 | SwarmNet | Drone task allocation | Graph Neural Network |
| M2 | SurvivorNet | Aerial person detection | YOLOv8n |
| M3 | PathRL | Autonomous drone flight | PPO Reinforcement Learning |
| M4 | SupplyOpt | Delivery route optimisation | Genetic Algorithm + MARL |
| M5 | DamageMap | Terrain damage classification | Random Forest |

## Tools Used
Python, Google Colab, PyTorch, Ultralytics YOLOv8, 
Stable-Baselines3, DEAP, LasPy, Roboflow

## Results Summary
- SwarmNet: 100% task allocation accuracy
- SurvivorNet: 91.4% mAP@0.5
- PathRL: 878% improvement over random baseline
- SupplyOpt: 40.4% delivery distance reduction
- DamageMap: 100% terrain classification accuracy
