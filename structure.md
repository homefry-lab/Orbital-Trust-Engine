Project Orbital Trust: Data Schema v1.0
Goal: Correlate maneuver history with real-time satellite health to generate Risk Scores.
1. conjunction_events
Tracks potential collisions identified by SSA (Space Situational Awareness) providers.
2. telemetry_logs
Captures the "Heartbeat" of the satellite (Battery, Thermal, Thruster Status) during the event window.
3. maneuver_verification
The "Truth Table." Compares the planned move vs. the actual change in orbit to flag discrepancies.
