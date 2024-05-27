# UCL COMP0123 Multi-agent Artificial Intelligence (2023/24)

This repository contains the first coursework I completed for my MSc module [COMP0123 Multi-agent Artificial Intelligence](https://www.ucl.ac.uk/module-catalogue/modules/multi-agent-artificial-intelligence-COMP0124).

The second coursework is a group research project on a self-selected multi-agent problem. Our group worked on the issue of prioritising agents in multi-agent path finding when conflicts occur. Checkout the [mapf-priority-study](https://github.com/chan-yc/mapf-priority-study) repository for more details of the research project.


## Tasks for coursework 1

1. **Matrix Game (1)**
   - Solved and analysed a matrix game by hand.

2. **Matrix Game (2)**
   - Solved a matrix game using NashPy.
   - Implemented the [support enumeration](https://nashpy.readthedocs.io/en/stable/text-book/support-enumeration.html) algorithm to find Nash equilibria.

3. **Repeated Game**
   - Implemented several agents with the following strategy:
     - Grim Trigger
     - Tit for Tat
     - Limited Punishment
     - All Defect
   - Implemented a reinforcement learning agent using Q-learning with tabular value update.

4. **Congestion Game**
   - Solved and analysed a congestion game.

5. **Bertrand Model of Oligopoly**
   - Modelled market competition with 2 firms.
   - Simulated the Bertrand model and analysed results.


## Python Environment

Requirement: `python=3.11`

    pip install -r requirements.txt