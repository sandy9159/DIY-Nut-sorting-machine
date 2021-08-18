# DIY-Nut-sorting-machine

![239541ad-b709-4fe6-8deb-2059ffff15d8](https://user-images.githubusercontent.com/19898602/129914285-0f645a18-3fed-4c89-b457-fbd486fc878e.PNG)


Hello friends in this video I tried to make a nut sorting machine, 

nuts and bolts are the essential part of any workshop but every now and then those tiny nuts of different size get 

assorted and its quite frustrating to sort them out this tiny machine will help you 

to sort them out it can sort M8, M6, M5, M4, M3 sizes this machine not have 100% accuracy 




## Component used 
 
> BO DC motor

> DC motor speed control board

> 12mm wood

> ON/OFF Switch

> potentiometer

> 8mm shaft holder 


## DC MOTOR SPEED CONTROL PCB

This the circuit diagram of speed control PCB 

![image](https://user-images.githubusercontent.com/19898602/129914741-251cba90-415a-484a-8a38-b94a992b960e.png)

This is a pretty cool circuit that allows you to control the speed a DC motor of considerable size

Followings are the component used in the circuit


![image](https://user-images.githubusercontent.com/19898602/129915282-53214abf-5f2d-4d99-9c3c-0bec60176886.png)

DC motor may be a purely inductive Load so if you would like to regulate the speed of the DC motor then we've to upper / lower the voltage for higher / lower speeds. 

but in practically higher voltage and lower voltage isn't that sort of possible so, during this case,

we use another sort of method which is named PWM better referred to as pulse width modulation.



The word PWM is additionally referred to as Pulse Width Modulation. Suppose there's a voltage of 5 volts which is popping on and off in an interval. 

This on / off signal is especially presented as duty cycles now if there's a 50% duty cycle within the output voltage are going to be 50% of 5 volts so it'll be nearly 2.5 volts. The duty cycle are often 25% of fifty or 90% or maybe 100%. 

so now you'll calculate what the voltage is going to be when the duty cycle is going to be during a certain percentage. Now this PWM Pulses runs the transistor and it runs the Motor.


![image](https://user-images.githubusercontent.com/19898602/129915627-2d14fafc-3ff7-434d-aa31-7e932ee2b321.png) ![image](https://user-images.githubusercontent.com/19898602/129915648-55bc75a4-dd7c-41fb-9109-a3f386c30347.png)


Here are Some Pictures for creating the Circuit. I even have made the DC Motor Speed Controller Circuit within the PCB for creating the circuit as simple as possible. 

you'll also make the circuit within the Breadboard. But there could also be loose connection So I even have Directly Soldered all Components. 

So, there'll not be any loose connection.

I always prefer visit [JLCPCB.com](https://jlcpcb.com/IAT) because they offering high quality PCB in reasonable price in very short time so why go elsewhere 
visit [JLCPCB.com](https://jlcpcb.com/IAT) for High quality PCB and discount coupons on first order.


![image](https://user-images.githubusercontent.com/19898602/129916137-da650983-277d-4ccd-b31a-75ad9a5e2c36.png) ![image](https://user-images.githubusercontent.com/19898602/129916214-084ea734-5112-4413-8549-c08ed65e49b6.png) ![image](https://user-images.githubusercontent.com/19898602/129916509-12b63531-5643-4db5-a0b9-779b94285da0.png) ![image](https://user-images.githubusercontent.com/19898602/129916646-484321c3-ad7e-486b-9158-dae533940d88.png)


First of all 3D printed all the parts.

I have design such parts in fusion 360 and exported them in STL files and printed using my artillery 3D printer

I have chosen PLA filament because is enough for this job, all the parts which I have printed are 20% infill

this is the link of 3D STL files if you need to download them

https://www.thingiverse.com/thing:4931463



![Nested Sequence 03](https://user-images.githubusercontent.com/19898602/129917644-41441a2e-dca0-45b1-a989-7c350a54ef62.gif)


![image](https://user-images.githubusercontent.com/19898602/129917304-bbac28ca-a4b5-4dd6-aca6-bee5e3236a20.png)




![image](https://user-images.githubusercontent.com/19898602/129917845-6be300ea-c382-4009-a062-9001f226de45.png)

I cut 12mm wooden sheet in required dimension. Then I applied masking tape where I need to drill holes.

I drilled holed to mount most of the components 

I have mounted SHF8 8mm shaft holder this will hold the main shaft on which our turn table rotate

I have make this arrangement like if you need to adjust the distance between turn table and guider you can do this just by losing the nut on SHF8

LMK8UU linear bearing used in this project this bearing is rigidly connected with the turn table 

with the help of 2 2mm screws, then this bearing slid to the top end of 8MM SS rod. 

I have design a gear that is fitted on the shaft of SHF8 bearing and get engage with the gear of DC motor 

This setup you can visualize in below animation



![Nested Sequence 04](https://user-images.githubusercontent.com/19898602/129920399-83e2f89c-4f9d-47c9-97e8-c02b593bcc7e.gif)



This is the BO dc motor, which I have used as the main engine of the machine

Bo motor (Battery Operated) lightweight DC geared motor which gives good torque and rpm at lower voltages. Here you can get bo motor with varying rated speed. 

This motor can run at approximately 200 rpm when driven by a single Li-Ion cell. Great for battery operated lightweight robots.

The motor has the ability to operate with minimum or no lubrication, due to inherent lubricity. The motor is ideal for DIY enthusiasts. 

This motor set is inexpensive, small, easy to install, and ideally suited for use in a mobile robot car. They are commonly used in our 2WD platforms.

![image](https://user-images.githubusercontent.com/19898602/129923537-4eee35fd-bf25-4d2c-8082-e8b40fecbc89.png)


![image](https://user-images.githubusercontent.com/19898602/129923717-d9c1a777-d9cb-4231-ba07-6f0ac70bb6e4.png)


As shown abowe I placed the circuit aside of BO DC motor 
I also attached the wiring diagram how I connect the DC motor Potentiometer with he PCB

![image](https://user-images.githubusercontent.com/19898602/129924037-9c0da9cd-9487-4bd8-9078-511ee8f0d3de.png)


In this way the construction of machine is completed As soon as we power the machine it is ready to start

We can plug 12V DC using 5MM jack and turn the SPDT switch on to feed power to the motor, at last we can control the 

speed of turn table by rotating the knob, the different size of nuts get separated due to the pre-planned gap between

turn table and guider. and this nut then drop into there respective pockets.



![image](https://user-images.githubusercontent.com/19898602/129924266-e598d1de-081a-42b4-bebb-77b1e571674b.png)







