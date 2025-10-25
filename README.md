# Ex No: 06 - Design & Implementation of 2-Bit Multiplier Using Cadence Virtuoso

## Aim
The aim is to design and implement a **2-bit Multiplier** using **Cadence Virtuoso** and verify its functionality through transient analysis simulation.

## Tools Required
### Cadence Virtuoso Suite
- **Virtuoso Schematic Editor** (for circuit design)
- **Spectre Simulator** (for circuit simulation)

### Process Design Kit (PDK)
- CMOS technology library

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure

### 1. Launch Cadence Virtuoso Environment:
- Open the **Cadence Virtuoso** tool and set up the working library.
- Create a new **schematic cell view** for the **2-bit Multiplier** design.

### 2. Schematic Design:
- Select **NMOS and PMOS transistors** from the library.
- Construct the **2-bit Multiplier circuit** using **AND and ADDER logic gates**.
- Connect the inputs (**A1, A0, B1, B0**) and outputs (**P3, P2, P1, P0**) properly.

### 3. Simulation:
- Check the design for **errors** and proceed with simulation.
- Launch the **Analog Design Environment (ADE)**.
- Perform **transient analysis** to verify the multiplication logic.
- Set up **input stimulus** and analyze the **output waveform**.

## Circuit Diagram

![image](https://github.com/user-attachments/assets/a56c4672-c7a5-44a8-908f-860243dc365d)


## Truth Table for 2-Bit Multiplier

![image](https://github.com/user-attachments/assets/fdb01f7d-60c1-4605-8462-c4dd954c5602)


## Schematic Diagram

### Schematicand Symbol of 2-Input AND Gate:

![Screenshot 2025-05-10 160454](https://github.com/user-attachments/assets/7a700f59-c4b4-4006-b791-0a4edf7d1e57)

<img width="1920" height="1080" alt="Screenshot 2025-10-25 153043" src="https://github.com/user-attachments/assets/a1aeb6b1-8ebe-4b18-b72c-9f57a86314c8" />


### Schematicand Symbol of 2-Input EX-OR Gate:

![Screenshot 2025-05-10 160515](https://github.com/user-attachments/assets/880ad1be-e8b3-4111-b2ea-2b2c7eb1fd14)

<img width="1920" height="1080" alt="Screenshot 2025-10-25 152828" src="https://github.com/user-attachments/assets/45b9db64-bd54-4eaf-a9b4-af9a57342f2b" />


### Schematicand Symbol of Half Adder:
![Screenshot 2025-05-10 160535](https://github.com/user-attachments/assets/5d98f983-d6b7-42b9-8f16-17407b2010b2)

<img width="1920" height="1080" alt="Screenshot 2025-10-25 153010" src="https://github.com/user-attachments/assets/d3af4b0b-9c86-414b-9dd9-1bafc9651684" />


### Schematic of 2-Bit Multiplier:
<img width="1920" height="1080" alt="Screenshot 2025-10-25 152310" src="https://github.com/user-attachments/assets/1b522fb1-7a4c-41e2-a9fd-53cc1fff3a55" />


## Output
### Transient Analysis Output:
<img width="1920" height="1080" alt="Screenshot 2025-10-25 151850" src="https://github.com/user-attachments/assets/b17e8691-3c05-41e5-af53-342f2c394879" />


![image](https://github.com/user-attachments/assets/55864d90-af08-4836-bc90-4cbba80573f8)


<img width="1920" height="1080" alt="Screenshot 2025-10-25 152332" src="https://github.com/user-attachments/assets/76f0d173-73ea-4f86-8d27-4dd49d100696" />


Run Time : 200ns

## Results
1. Successfully designed the **2-bit Multiplier** schematic using **Cadence Virtuoso**.
2. Performed **transient analysis**, verifying the correct operation of the **Multiplier**.
3. Observed **correct multiplication behavior** in response to input signals.
