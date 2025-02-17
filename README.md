# Vacuum Former
An affordable vacuum former capable of forming medium to large bucks and molds. The system must also be safe for anyone to use in both hardware and electronics (as this requires mains).

![Project_Image](.assets/Vacuum%20Former%20Design.png)

## Features
* Hybrid Frame - Rigid aluminium combined with cheap cement fiber boards results in a fireproof frame.
* RCBO - Short, fault and overcurrent protection.
* SSR - PWM based temperature control.

## [Hardware](/Hardware/README.md)
The frame is designed to be collapsible so it is easily stored. The heater box, material frame and base plattern uses the same 440mm x 640mm aluminium 2020 frames which makes it easy to
fabricate and assemble. All components that get close to the heatsource is fireproof and areas that are not subject to heat are 3D printed to both save cost and time to construct.

## [Embedded](/Embedded/README.md)
Although dangerous, many safety features were implemented to reduce the risk of injury. This includes breakers and rcbos to detect shorts, faults and if the user accidentally touches the
live wires. All electronics are rated to and beyond what is required to run the system of 240VAC at 20A, this does mean however, that the user must have a port which can supply 15A and
beyond if you want to run the heater box. The average house hold outlet should provide 10A at 240VAC, however if your in the Americas you'll use 110VAC. This means in both senarios,
you will have to find a high current compatible port or else you will trip a breaker. If you dont have one, then you must remove 2 of the heating elements as each of them uses 1KW. This 
will however reduce the total amount of heat you can provided and may not be able to rais the temperature enough to heat difficult to form materials such as polycarbonate which requires 
around 240C to form properly.

## Roadmap
* Milestones: Hardware Assembly Complete
* Work In Progress: Electrical Wiring
* Work In Progress: Electrical Box
* Work In Progress: Controller Box