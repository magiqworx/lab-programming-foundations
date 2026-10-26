# Lab Proof: HomeGuard Security System Simulator

- **Program Path:** `homeguard_system.ipynb`
- **Run Command:** "Run All" in VS Code / Jupyter Notebook

## Output Summary
The simulator successfully executes multiple time iterations, reading sensor values (motion, temperature, door, smoke) and correctly evaluating rules against the system mode (e.g., AWAY). The output demonstrates active alerts when thresholds are breached.

## Edge Case Explanation
- **Scenario:** The temperature drops to 34°F while the system is in *AWAY* mode.
- **Handling:** The system immediately triggers a critical safety alert and logs the event to notify the homeowner, preventing potential frozen pipe damage.