# Gateway
Home Entry Automation 

Gateway is meant to function and act as a modern convenient upgrade to the home. 
Our project atcs as a home key fob, but has the added aditions of phone integration, as well as providing a manual option. The fob is designed to act directly with and control house lighting and locking.
The project is built into two major components. 
First, a box fits on your home door. An RFID scanner takes the place of the key slot you would find for bolt locks on your door. On the other side of the door is our locking mechanism. The locking mechanism is attached to the RFID via two bolts that run throw the door cavity. Inside the locking mechanism is an Arduino Nano, Servo motor, Bluetooth HC-06 module, and servo motor arm. Two manuel control buttons are also housed to the face plate of the locking module. The locking system is contained in a wooden box structure.

The second component is the light module. The module is comprised of a light plate designed to fit over a rocker light switch. Integrated into the plate is another servo motor with custom built arms which keep contact with the light switch. The power source for the system is also housed here. The entire light system is housed in a built wooden casing.  

The unifying system comes in our bluetooth and app system. We've developed the gateway App which has direct control over both the lighting system and locking system. Each aspect can be controlled independently of one another, allowing the customer to have both a preference for sytem, and a back-up if needed. 

Altogether, we have a project which can be the next common household implementation 

Below are the contnets of each file  

**Assembly** contains assembly intructions, and completed examples of each component 

**Arduino_Code** contains the code needed to run the sytem which will be uploaded to the arduino Nano. Notes and comments included  

**List of Materials** contains all parts and pieced required to build the gateway system including pricing and suggested retailers 

**Lock Mechanism/CAD** contains all of the 3D printed parts, box dimensions, and assembly diagrams for the Lock Components  

**Gateway_Circuit_Diagram** contains image containing the Gateway circuitry across both the lock and light components  

**Gateway_Phone_App** contains the download link the the phone app compatible with with Gateway System via bluetooth as well as 
                      develoment intrsutctions 

**Gateway_Flowchart** contains the coding pathing outline for how the sytem communicates with both itself, and the phone application 

**Switch Mechanism/CAD** contains all of the 3D printed parts, box dimensions, and assembly diagrams for the Light Switch Components 

