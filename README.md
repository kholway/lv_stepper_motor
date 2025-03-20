# LV Stepper Motor

This is a project I built in LabVIEW to provide control for a stepper motor. Input via a GUI was conveyed to hardware which generated electrical signals for precise control of the position of the motor.

## Control Panel GUI
![GUI with control pannel for motor operation](./front_panel.png)

## Program Logic
![Diagram of program logic](./block_diagram.png)

## Usage
Viewing the code requires LabVIEW. Using the code would require DAQ-MX drivers, an appropriate NI DAQ device, and, of course, a stepper motor to be controlled. The proram would need to be modified so that the signal corresponds to the specs of the motor in question.