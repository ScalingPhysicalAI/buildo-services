# buildo — Humanoid Services

Monorepo for all services running on the humanoid robot. Each top-level
directory under `services/` is a placeholder for one service module.

Simulation is **out of scope** for this repo — it lives in a separate project.

## Services

| # | Service | Notes |
|---|---------|-------|
| 1 | [connectivity](services/connectivity) | wifi, hotspot |
| 2 | [startup](services/startup) | hello-world bring-up: check, hello |
| 3 | [wheel](services/wheel) | ROS |
| 4 | [torso](services/torso) | ROS |
| 5 | [arm](services/arm) | ROS |
| 6 | [hand](services/hand) | |
| 7 | [watchdog](services/watchdog) | safety |

## Status

Placeholder scaffold only — no implementation yet. Each service directory
has a stub README describing its intended scope.
