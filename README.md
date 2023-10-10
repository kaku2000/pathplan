# Hybrid-A*
Motion Planner for a Car based of Kinematic & Reeds-Shepp Node expansions and a combination of Holonomic & Non-Holonomic Cost Function.

## Dependencies
```
pip install -r requirements.txt
```
 
## Run
```
python scripts/hybridAStar_ghe.py
```

<!-- 1. python3
2. [CurvesGenerator](https://github.com/zhm-real/CurvesGenerator) -->

## Results
<!-- Path & Footprint           |  Node Simulations & Animation
:-------------------------:|:-------------------------: -->
Same case: 
 data/ghe/original.mov

Long Distance : 
 data/ghe/long-distance.mov

Others : 
 data/ghe/weird.mov
 data/ghe/04.mov

## Refrences
1. https://github.com/zhm-real/MotionPlanning
2. https://blog.habrador.com/2015/11/explaining-hybrid-star-pathfinding.html
3. https://github.com/karlkurzer/path_planner