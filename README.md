# Mod14 Counter Verification

## Overview
This project contains the verification environment for the Mod14 Counter design using UVM methodology. It includes RTL code, testbenches, agents, and simulation results along with coverage and topology snapshots.

## Folder Structure
- `rtl/` : Contains all RTL source files.  
- `tb/` : Contains the testbench files.  
- `src_agt/` : Source agent for UVM environment.  
- `dst_agt/` : Destination agent for UVM environment.  
- `test/` : Test files and sequences.  
- `sim/` : Simulation outputs and logs.  
- `images/` : Contains coverage and topology screenshots.

## Screenshots

**Coverage Report:**
![Coverage](images/Screenshot%20(326).png)

**Topology:**
![Topology](images/Screenshot%20(334).png)

## How to Run
1. Clone the repository:
```bash
git clone https://github.com/YourUsername/mod14_counter_verification.git
cd mod14_counter_verification
## Notes
- Make sure you have all the software needed to run the project (like a SystemVerilog simulator and UVM libraries).  
- If you add new tests or RTL files later, update this README so it shows the changes.
