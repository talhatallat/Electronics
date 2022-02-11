# Flip-Flop

## Laboratory Aim

The purpose of the laboratory is to make a memory data type flip flop in Vivado.

![image](https://user-images.githubusercontent.com/73076876/153520965-0614c546-9bec-4711-ae09-13c4794c029c.png)

This is a symbol for memory D type flip flop. The D-type flip-flop is a modified Set-Reset flip-flop with the addition of an inverter to prevent the S and R inputs from being at the same logic level. 

The D type flip flop is the most important of the clocked flip flops as it ensures that the inputs S and R are never equal to one at the same time. 
The D type flip flop are built from a gated SR flip flop with an inverter added between the S and the R inputs to allow for a single for a single data input as the circuit is shown down below.

![image](https://user-images.githubusercontent.com/73076876/153520998-2cc32c81-028f-4662-84d6-835d1f727e3a.png)

Memory circuit functions by storing the voltage present on an input signal whenever they are triggered by a control signal whenever they are triggered by a control signal, and they retain that stored voltages until the next assertion of the control signal.
