# AR-Room-Raid
## Room Raid AR

Browser AR wave shooter. Play: https://valm66-ops.github.io/AR-Room-Raid/

- Camera + gyro for aiming; in-browser AI (Depth Anything V2 Small + SegFormer-B0 via Transformers.js) finds floor, walls and doors.
- Enemies spawn only from doorways and hallways the camera has seen.
- Walking: position tracking by [AlvaAR](https://github.com/alanross/AlvaAR) visual SLAM (`alva_ar.js`, GPL-3.0), scaled using the floor plane.
