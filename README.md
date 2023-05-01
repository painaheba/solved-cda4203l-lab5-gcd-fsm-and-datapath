Download Link: https://assignmentchef.com/product/solved-cda4203l-lab5-gcd-fsm-and-datapath
<br>
<strong>Objective:  </strong>To implement RTL Design (structural datapath and behavioral controller) of Greatest Common Denominator (GCD) of two numbers to be tested on a FPGA board.

<strong>Description: </strong>Design a GCD for two 4-bit numbers. It will output the binary value of the greatest common divisor of those two numbers. The numbers will be input via the dip switches, the result will be output via the LEDs, and control is done via push buttons.




<ul>

 <li>Input X uses switches SW7-SW0.</li>

 <li>Input Y uses switches DIP9-4 to DIP8-1.</li>

 <li>Input START uses the pushbutton BTN0. This button needs to be debounced.</li>

 <li>Input RESET uses the pushbutton BTN3.</li>

 <li>Output GCD OUT uses LEDs LD7-LD0.</li>

 <li>Output DONE uses the LED LD9.</li>

</ul>

The data path components must be constructed structurally. You can create individual behavioral components (Adder, Comparator, Register, etc.) for each element in the data path. Registers are the only clocked component, and they should be triggered by the clock on the opposite edge than that of the Controller FSM. All non-register components must be purely combinational. Registers should have an enable signal for control, and a separate reset signal.

<ol>

 <li> Write structural Verilog for data path and behavioral Verilog for controller (FSM).  Use the design we discussed in the class.  The FSM Verilog code should strictly follow the FSM template.</li>

 <li>Synthesize the design and verify its functionality on the FPGA.</li>

</ol>

<strong>Deliverables: </strong>

Submit a zipped archive consisting of: (a) A concise report that includes your Verilog code and simulation results; (b) Verilog Models and Test bench.  Include a README file.

<strong>Report Organization (A template is provided on Canvas):</strong>

<ul>

 <li>Cover sheet</li>

 <li>Problem 1: Your design details, Verilog Code, Test Bench, and Simulation Results (Waveforms)</li>

 <li>Problem 2: Pin mapping file and Synthesis report.</li>

 <li>Feedback: Hours spent, Exercise difficulty (Easy, Medium, Hard)</li>

</ul>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>