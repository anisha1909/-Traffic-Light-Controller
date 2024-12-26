# Traffic Light Controller
 

Objective: 
To design, simulate, and implement a traffic light controller for an intersection using SystemVerilog, and emulate real-time traffic signal operations for Indian roads using an FPGA, LEDs, and a breadboard setup.  

Project Description: 
This project involves developing a traffic light controller that manages signal transitions for an intersection with two directions: North-South and East-West. The controller follows timing and sequencing logic typical of Indian traffic patterns, ensuring efficient traffic flow.  

 Key Features:  
1. Traffic Light Logic: 
   - Each direction is equipped with red, yellow, and green lights.  
   - Signals are controlled based on a predefined timing sequence to manage traffic efficiently.  

2. SystemVerilog Design: 
   - The design uses a finite state machine (FSM) to manage light transitions.  
   - States include green, yellow, and red lights for each direction, with appropriate delays for safety.  
   - Timing control ensures precise durations for each light phase, taking into account Indian traffic conditions.  

3. Simulation:  
   - The controller is first verified using simulation tools like ModelSim or Vivado Simulator.  
   - Testbenches simulate various real-world scenarios, including varying traffic densities and emergency conditions.  

4. FPGA Implementation: 
   - The validated SystemVerilog design is synthesized and implemented on an FPGA.  
   - Outputs are connected to LEDs on a breadboard to emulate real traffic signals.  
   - The hardware setup demonstrates the functionality in real time, providing a practical representation of traffic control.  



 Tools and Components:  
- Software: SystemVerilog, Vivado 
- Hardware: FPGA board ( Xilinx) , breadboard, LEDs, resistors, and connecting wires  

