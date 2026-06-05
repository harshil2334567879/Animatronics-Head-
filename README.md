# Animatronics-Head-
This is an Animatronics Head that will work on Raspberry Pi Picos. I will use 21 servos in it which consist of 2MG996r Servos for Jaw because the Jaw requires large torque and rest are 19 mg90 servos. We will use 3 raspberry Pi Picos each pico will handle a certain area of the Head.
The 1st pico will handle 2 Large and 9 mini servos for the mouth system. I have used 2 large MG996r servos for Jaw beacause the Jaw will require large amount of Torque to move cuz all the weight of the Head depends on it. Now the 2nd Pico will handle the eye mechanism will consists of 6 servos and the last Pico handles the Eye-Brows will contains 4 more servos which comes to a total of 21 Servos and 3 Raspberry Pi Picos.
Now the main problem is going to be the wiring as there are 21 servos totaling our no. up to 63 wires in the skull which is going to create a big mess. So I decided to choose a more practical but smart way to use custom PCB's for each Pico. These PCB's would have Pico headers and pins for servos and other electronic components for smooth movement. As I said 1 PCB for 1 Pico that's why we are using 3 PCB's for 3 Picos to control Mouth, Eyes and Brows. We'll add connection points so that we can connect the PCB's to each other.
We will use custom made 3d printed parts to make the skull and fix the components in it with the help of M3 and M4 screws. 
I will add Auto-Movement scrips in the Picos for Independent movement. 
To power this massive project, I'll be a 12v and 20A power supply with a Buck Converter to change the Voltage from 12v to 5v So that our Picos and Servos don't get fried. At the peak all the servos will draw around 15A of current, So our 12v and 20A power supply is enough to power this whole system. 
I am leaving the codes up in the "Codes" Section. 

This project was inspired by a YouTuber "Will-Cogley"

Author - Harshil
