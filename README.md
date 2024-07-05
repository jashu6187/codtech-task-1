Name:OBULANAYAKULAGARI NAGA JASWANTH <br>
Company:CODTECH IT SOLUTIONS <br>
ID:CT6WDS130 <br>
Domain:VLSI<br>
Duration:JUNE 2024 to 17Th JULY 2024” <br>
Mentor:SRAVANI GOUNI <br>
Over view of the project <br>
project:Design basic digital logic circuits like logic gates, adders, and multiplexers using
Verilog within the VLSI software. 

# Code
/**/logic gates <br>
module and_gate(input a, input b, output y); <br>
  assign y = a & b; <br>
endmodule <br>

module or_gate(input a, input b, output y); <br>
  assign y = a | b; <br>
endmodule <br>

module not_gate(input a, output y); <br>
  assign y = ~a; <br>
endmodule <br>
/**/adders <br>
module full_adder(input a, input b, input cin, output sum, output cout); <br>
  assign {cout, sum} = a + b + cin; <br>
endmodule <br>
/**/multiplers <br>
module mux_2to1(input [1:0] data, input sel, output y); <br>
  assign y = (sel) ? data[1] : data[0]; <br>
endmodule <br>

objective:
A digital logic design is a system that uses simple values to produce functions, perform operations and define the input and output of any digital circuit. It is mostly used in electrical and computer engineering to develop the basic circuitry for electronic devices, microprocessors, and hardware.
![](https://github.com/jashu6187/codtech-task-1/blob/main/Screenshot%202024-07-03%20183940.png)
![](https://github.com/jashu6187/codtech-task-1/blob/main/Screenshot%202024-07-03%20185653.png)
![](https://github.com/jashu6187/codtech-task-1/blob/main/Screenshot%202024-07-03%20185739.png)
![](https://github.com/jashu6187/codtech-task-1/blob/main/Screenshot%202024-07-03%20190329.png)
![](https://github.com/jashu6187/codtech-task-1/blob/main/Screenshot%202024-07-03%20190453.png)
![](https://github.com/jashu6187/codtech-task-1/blob/main/Screenshot%202024-07-05%20171505.png)
![](https://github.com/jashu6187/codtech-task-1/blob/main/Screenshot%202024-07-05%20172104.png)
