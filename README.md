This project implements a UART(Universal Asynchronous Receiver Transmitter) Receiver in Verilog HDL using a Finite State Machine (FSM) architecture. The receiver captures serial data from UART transmission line, samples the incoming bits according to the configured baud rate, and reconstructs then into an 8 bit parallel data word.

The design follows the standard UART frame format: -> 1 Start Bit -> 8 Data Bits -> 1 Stop Bit -> No Parity

The receiver is designed to operate at 115200 baud with a 25MHz system clock, requiring approximately 217 clock cycles per bit.	
				
