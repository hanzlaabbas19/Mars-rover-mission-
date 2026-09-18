# Lab Task 3: Mars Rover Mission Control System

## 1. Requirements Identification (from Engineering Notes)

## Functional Requirements (FRs)
### FR-01:
The system shall receive movement commands from Mission Control and execute valid commands.
### FR-02: 
The system shall report the rover's current position, battery level, temperature, and communication status.
### FR-03: 
The system shall validate and reject invalid or unauthorized commands.
### FR-04: 
The rover shall enter Safe Mode within 3 seconds when
battery temperature exceeds the critical threshold or
battery capacity falls below the defined emergency level.

### FR-05: 
Mission Control shall receive command execution status updates.
### FR-06: 
All commands and critical rover events shall be recorded with timestamps and operator IDs for logging.
## Non-Functional Requirements
### NFR-01 (Reliability/Fault Tolerance):
The system shall continue operating despite temporary communication interruptions.
### NFR-02 (Security):
Only authenticated Mission Control operators shall be permitted to issue rover commands.
### NFR-03 (Performance):
Command processing should complete within 5 seconds after a command is received by the rover.
### NFR-04 (Scalability):
The system should support communication with multiple rovers simultaneously.
