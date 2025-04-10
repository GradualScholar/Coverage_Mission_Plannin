# Coverage_Mission_Plannin

🚁 Multi-UAV Dynamic Coverage Task Allocation Framework
A novel two-stage task allocation framework for dynamic multi-UAV collaborative coverage missions. This project addresses the fundamental trade-off between global optimization and real-time adaptability, enabling UAV swarms to handle highly dynamic environments.

🚀Run the main program:

    python main.py
    
This will launch the full simulation, including both the static task allocation (enhanced NSGA-II) and the dynamic reallocation phase (auction-based algorithm under dynamic events).

🌐 Key Features
Two-stage task allocation:

Centralized static phase: Enhanced NSGA-II algorithm with:

    ·Dual-population initialization
    ·Path-exchange crossover
    ·Multi-strategy mutation


Distributed dynamic phase:

    ·Adaptive auction-based algorithm using ring communication topology
    ·Supports 6 dynamic events: UAV failure, UAV addition, node addition/removal, priority tasks, and re-exploration

🔧 Applications
Ideal for:

    ·Disaster relief and emergency response
    ·Infrastructure inspection
    ·Smart agriculture (e.g., pesticide spraying, irrigation)

📎 Paper & Citation
If this project helps your research, please consider citing our work. 

    Article title: Research on Two-Phase-Based Distributed Cooperative Dynamic Coverage Mission Planning for Multi-UAV Systems
