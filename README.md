# buildo — Humanoid Services

Monorepo for all services running on the humanoid robot. Each top-level
directory is a placeholder for one service module.

Simulation is **out of scope** for this repo — it lives in a separate project.

## Services

| # | Service | Notes |
|---|---------|-------|
| 1 | [connectivity](connectivity) | wifi, hotspot |
| 2 | [startup](startup) | hello-world bring-up: check, hello |
| 3 | [wheel](wheel) | ROS |
| 4 | [torso](torso) | ROS |
| 5 | [arm](arm) | ROS |
| 6 | [hand](hand) | |
| 7 | [watchdog](watchdog) | safety |

## Status

Placeholder scaffold only — no implementation yet. Each service directory
has a stub README describing its intended scope.
