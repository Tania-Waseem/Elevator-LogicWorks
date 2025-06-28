# Elevator Simulation – LogicWorks Project

## Overview

This project simulates a basic **elevator control system** using **LogicWorks**, a digital circuit design and simulation tool. The system is designed to handle elevator movement between floors based on user input, implementing core concepts of digital logic design including **state machines**, **encoders**, **decoders**, **flip-flops**, and **timing control**.

---

## Features

- Supports elevator movement between **3 floors** (Ground, 1st, 2nd)
- Uses **input switches** to simulate floor requests
- Implements a **finite state machine (FSM)** to handle elevator logic
- Includes **LED indicators** for:
  - Current floor
  - Requested floor
  - Elevator moving up or down
- Uses **clock pulses** to simulate timing

---

## Components Used

| Component          | Description                          |
|--------------------|--------------------------------------|
| Switches           | For user floor requests              |
| Flip-Flops (D/T/JK)| For memory and state transitions     |
| LED Indicators     | Display current status               |
| Counters           | To manage floor levels               |
| Comparators        | To check requested vs. current floor |
| Clock Generator    | To simulate elevator movement timing |
| Multiplexers       | For output control                   |

---

## How It Works

1. **User Input**: A user presses a switch corresponding to the desired floor.
2. **FSM Logic**: The elevator's control logic evaluates:
   - Current floor
   - Requested floor
   - Direction to move
3. **Movement**: The elevator "moves" (via counter/LEDs) one floor per clock cycle.
4. **Arrival**: Once at the target floor, the elevator stops and updates the state.

---

## Running the Simulation

1. Open **LogicWorks** software.
2. Load the `.cct` (circuit) file:  
   `ElevatorSimulation.cct`
3. Press the **Play** button to start the simulation.
4. Use the **switches** to request a floor.
5. Observe the **LEDs** for movement and current floor status.





