# Differential_amplifier-
## REG NUM :Surjini.R
## NAME :25015534
## EXPERIMENT 3:Design a CMOS Differential Amplifier and find out the Transient, DC and OP analysis.
## Aim:
To Design CMOS Differential Amplifier and Perform Transient, DC and OP analysis.

## ToolsUsed:
VirtuosoSchematicEditorisusedforthedesignandanalysis.

## Theory:
A differential amplifier circuit amplifies the difference of any two input signals and rejects any two common signals. The ideal characteristics of an amplifier are infinite gain, infinite bandwidth and infinite common mode rejection ratio, high input impedance and low output admittance, less distortion,sensitivity.Alsoit has less harmonic distortion and increased output voltage swing and the performance of the circuit is measured by its characteristics.

## Procedure:
•	Click  new -> library->attach to an existing technology library gpdk180(in technology file)
•	new->cellview ->(nameofthelayout)
## Forschematic:
A.)TRANSISTOR DIAGRAM:

<img width="591" height="525" alt="DIFFRENTAIL AMPLI DIAG" src="https://github.com/user-attachments/assets/c0e599d3-952c-4909-a2f2-72e03e56de8d" />

B.)CADENCE DIAGARAM

•	PickthecomponentsNMOS,PMOS,ground,VDDandvoltagesource.
•	Connectthewireaspertheschematic diagram.
<img width="1067" height="568" alt="image" src="https://github.com/user-attachments/assets/50200970-a0dc-4229-943e-cd4cc8db4291" />
Fig:CMOSDifferentialAmplifierSchematic

## For symbol:
<img width="1067" height="602" alt="image" src="https://github.com/user-attachments/assets/3e6aae96-b512-45ea-88a6-49a862dbf445" />
Fig:CMOSDifferentialAmplifierSymbol

## Transient Analysis:
a)	In the Analysis section, select transient.
b)	In the stop time type 600n and click OK.
c)	In the transient Analysis section, turn on Save transient Operating Point. 
d)	Check the enable button and then click Apply.
e)	Click OK in the Choosing Analyses Form.

## Execute Outputs:
To be plotted–Selecton Schematic in the simulation window. Follow the prompt at the bottom of the schematic window, Click on output net Vout, input net Vin of the Inverter.
Execute Simulation:
Netlist and Run in the simulation window start the Simulation.
When simulation finishes,theTransient plots automatically will be poppedup along file.

## WAVEFORM:
<img width="1912" height="938" alt="out diff amp 1" src="https://github.com/user-attachments/assets/14125458-14a5-41fa-93f9-b5a6ee8def67" />

## RESULT:
Design of CMOS Differential Amplifier Transient and op analysesis performed.




