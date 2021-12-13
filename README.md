# MINIATURE WASHING MACHINE 


## PRODUCT DESIGN
The team agreed upon the project goal to go with the Washing Machine given in the project 
guideline. As outlined in the guideline, the DC motor will have 3 different cycles. 
1. The washing cycle, where the motor will spin in both directions, which will allow the clothes 
to be washed thoroughly. After spinning one way, the motor will come to a complete stop 
before changing directions to make sure no electrical and mechanical equipment is 
damaged.
2. Next is the rinsing cycle where the motor will spin in a single direction at relatively constant 
speed despite the increase and decrease in load. This is when the water enters the 
 Manish Nath, Jeong Bin Lee, Lucien Tran
Renewable Energy Systems A2020 5
machine to dilute the detergent and flows out again constantly changing the load of the 
machine.
3. The final step is the spinning cycle where the moisture from the clothes will be drained. 
The motor will spin at different speeds, starting slow, then increasing speed up to a limited 
maximum speed and slowing down until it comes to a complete stop. This will be achieved 
by changing the duty cycle from 0% to 40%, then from 40% to 80%, and finally 0% duty 
cycle, letting the motor slow down to a complete stop.
A feature the project will also include is to have an emergency button to stop all functions without 
damaging components and stopping the motor within a short time. The team also discussed that 
this will be more like a pause button so that if the button is pressed within a timeframe, the machine 
will continue the cycle process

## PCB DESIGN

PCB includes:
* 2 input PWMs to a full bridge converter.
* outputs to a motor
* Available input from generator to arduino for measuremnets
