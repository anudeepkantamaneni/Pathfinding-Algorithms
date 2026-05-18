# Advanced Pathfinding Simulator

This is a Python + Pygame pathfinding project for robot-style navigation experiments.

## Features
- A* search
- Dijkstra search
- BFS
- Weighted terrain: road, sand, water
- Moving obstacles
- Automatic replanning when a moving obstacle blocks the current route
- Complex default map with bottlenecks and detours

## Install
```bash
pip install -r requirements.txt
```

## Run
```bash
python advanced_pathfinding_sim.py
```

## Controls
- `1` = A*
- `2` = Dijkstra
- `3` = BFS
- `W` = wall tool
- `E` = erase tool
- `S` = sand terrain
- `A` = water terrain
- `R` = road terrain
- `Q` = place start
- `G` = place goal
- `M` = load complex map
- `X` = clear all
- `C` = clear path marks
- `D` = toggle dynamic obstacles mode
- `SPACE` = run planner

## Notes
- A* is the best default for fast grid planning.
- Dijkstra becomes useful when terrain weights matter.
- BFS is mainly useful when all movement costs are equal.
