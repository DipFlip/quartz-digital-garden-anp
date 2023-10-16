---
dg-publish: true
---

Pathfinding algorithms for covering an area:
- STC (Spanning Tree Coverage) tries to cover an area by creating a minimum spanning tree that connects all points in a given region.
- Boustrophedon (also called lawn mower) patterns are ones where an area is covered by systematically moving in rows alternating direction back and forth.


Pathfinding algorithms to get to a point
- **A\*** is perhaps the most well-known algorithm. It's fast and optimal in finding the shortest route between two points.
- **RTT** (Rapidly-Exploring Random Trees) quickly explore space by branching out towards unexplored regions. It can be faster than A* and better at finding collision-free paths.
- Wavefront is propagating a “wavefront” from the start location to a goal. This method cannot handle steps of varying cost.
- Dijkstra's Algorithm is similar to wavefront but can handle steps of different costs (harder to pass, already covered et. c.)

Useful repo for coverage code: https://github.com/18alantom/CoveragePathPlanning