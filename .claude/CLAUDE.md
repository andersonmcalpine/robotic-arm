## Project: Robotic Arm
- Hardware: ODrive motor controller
- Language: Python (ODrive SDK)
- Non-blocking control loops preferred — avoid time.sleep() in motion logic
- Document ODrive register names, axis states, and calibration sequences in comments
- Prefer descriptive variable names for joint/axis references

## Verify
- Lint: `python -m flake8 .`
- Format check: `python -m black --check .`
- Tests: `python -m pytest`

## Git
- Remote: git@github-personal:andersonmcalpine/robotic-arm.git
- Identity: andersonmcalpine / anderson.mcalpine@gmail.com
