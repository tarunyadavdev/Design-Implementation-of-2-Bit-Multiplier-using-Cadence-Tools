# Ex No: 06 Design-Implementation-of-2-Bit-Multiplier-using-Cadence-Tools

### Aim:
To design and implement a 2-bit multiplier circuit using Cadence EDA tools, simulate its functionality, and to understand its application in digital arithmetic operations.

### Tools Required:
•	Personal Computer<br>
•	Cadence Virtuoso Software<br>

### S C H E M A T I C S I M U L A T I O N - PROCEDURE FOR CREATING THE SCHEMATIC SIMULATION -Commands to get into Cadence

1.	Right Click and open the terminal window<br>
2.	Type the following commands as follows and press enter.<br>
•	csh<br>
•	source /cadence/install/cshrc<br>
•	virtuoso <br>
### Procedure for Schematic simulation using Cadence

1.	Now two windows must open i) virtuoso/command interpreter window ii)”Whats New…”<br>
2.	Close the 2nd window<br>
3.	Use 1st window i.e virtuoso window (CIW) for further processing.<br>
i.	Create a New Library<br>
ii.	Create Schematic Cell view.<br>
iii.	Create the Symbol for schematic Cell view.<br>
iv.	Create the test Cell view.<br>
v.	Analog simulation by spectre<br>


### i)	Procedure for Creating New Library.
•	File –New – Library<br>
•	Name: Give name for ur library Ex: VLSILAB_EXP_1<br>
•	Enable Attach to an existing technology library, Click OK<br>
•	Attach the library to the technology library gpdk045.Click OK<br>
### ii)	Create Schematic Cell view.
•	Go to 1st window i.e virtuoso (CIW)<br>
•	File-New-Cell view<br>
•	Setup the new file form<br>
	Library: Select the one you created.<br>
	Cell: Give the experiment name Ex: Inverter ViewSchematic<br>
	Type: Schematic press OK<br>
•	Add the required components from the libraries and make the connections.<br>
	Go to instance fixed menu or use shortcut key “I” from keypad to go instances<br>
	Click on browse. This opens the library browser<br>
	Now select the appropriate library for components like <br>
	Gpdk45 ------------------------nmos1v, pmos1v<br>
	Create Input and Output pins<br>
	Make the connections by using fixed narrow wire key<br>
	Click Check and Save button<br>

![WhatsApp Image 2024-11-14 at 13 58 46](https://github.com/user-attachments/assets/3371d175-e90a-45f1-b3c1-67447b94caf2)

 
### iii)	Creating the Symbol for schematic Cell view

•	In the schematic window, execute <br>
	Create – Cell view – From Cell view<br>
	Check Lib Name, Cell Name, From View name must be schematic Press ok<br>
•	Now Symbol generation form appears. Click Ok If No changes required<br>
•	A new window with with default symbol is created.<br>
•	Edit the symbol if you want to give actual symbol shape else continue.<br>
•	Execute Create-Cell view-from cell view<br>
•	Library Name and Cell Name must be same which you have used for schematic. Press OK<br>
•	Check for the position of pin side.Prss OK<br>
•	Edit for the shape by Create-Shape-Choose required options to edit.<br>

![WhatsApp Image 2024-11-14 at 13 58 43 (2)](https://github.com/user-attachments/assets/7a199260-0e20-41f6-a7d6-83f6698b9ae1)



### iv)	Creating the new test cell view

•	Go to CIW window, Execute File-New-Cell view<br>
	Setup the new file form<br>
	Library: Select the one you created.<br>
	Cell: Cell name must be different from the name used in schematic cell view. Ex: Inverter_test<br>
	View: Schematic<br>
	Type: Schematic press OK<br>
•	Follow the step 3(ii) d to make the required connections<br>


![WhatsApp Image 2024-11-14 at 13 58 43 (3)](https://github.com/user-attachments/assets/13baab00-f679-433d-a50b-8d333f2096b1)

 

### Analog simulation by SPECTRE.
•	In test cell view window<br>
•	Launch – ADE L(Analog Design Environment)<br>
	Execute Setup—Simulation/directory/Host A new window opens<br>
	Set the simulation window to spectre and click ok<br>
	Execute Analysis – Choose. A window opens.<br>
	Select the type and set the specifications and press OK<br>
	Execute Output s—to be plotted – Select on Schematic<br>
	Then Select the INPUT WIRE(Vin ) and OUTPUT WIRE(Vout) from your test Schematic using mouse<br>
•	Execute Simulation -- Net list and Run<br>

![WhatsApp Image 2024-11-14 at 13 58 44](https://github.com/user-attachments/assets/ac88f211-32e4-4ae2-970d-418d15933563)


For Transient Analysis Settings and Output
![WhatsApp Image 2024-11-14 at 13 58 45](https://github.com/user-attachments/assets/23e70e70-ef26-4aae-ab57-5dfba084ddcf)


![WhatsApp Image 2024-11-14 at 13 58 44 (1)](https://github.com/user-attachments/assets/dc3913a5-ba66-44a9-8d75-7218e3e20c5f)

  

### Results:
The design and implementation of the 2-bit multiplier using Cadence EDA tools were successfully carried out. The simulation results confirmed the correct operation of the multiplier for all input combinations. 
