# EXP02--Design-Implementation-of-Full-Custom-2-1-MUX-using-Cadence-EDA-Tools
Experiment -2 

**Aim:**
To design and implement a 2:1 multiplexer (MUX) circuit using Cadence EDA tools, analyse its functionality and performance, and understand the principles of digital logic design, including schematic creation, layout design, and simulation.

**Tools Required:**
•Personal Computer
•Cadence Virtuoso Software


**S C H E M A T I C S I M U L A T I O N**

**PROCEDURE FOR CREATING THE SCHEMATIC SIMULATION**

* Commands to get into Cadence:
1.Right Click and open the terminal window
2.Type the following commands as follows and press enter.
  •csh
  •source /cadence/install/cshrc
  •virtuoso 

* Procedure for Schematic simulation using Cadence:
1.Now two windows must open i)virtuoso/command interpreter window ii)”Whats New…”
2.Close the 2nd window
3.Use 1st window i.e virtuoso window(CIW) for further processing.
   *Create a New Library
   *Create Schematic Cell view.
   *Create the Symbol for schematic Cell view.
   *Create the test Cell view.
   *Analog simulation by spectre




i)Procedure for Creating New Library.
•File –New – Library
•Name : Give name for ur library Ex: VLSILAB_EXP_1
•Enable Attach to an existing technology library, Click OK
•Attach the library to the technology library gpdk045.Click OK

ii)Create Schematic Cell view.
•Go to 1st window i.e virtuoso(CIW)
•File-New-Cell view
•Setup the new file form
  Library: Select the one you a created.
  Cell : Give the experiment name Ex: Inverter View_Schematic
  Type: Schematic press OK
•Add the required components from the libraries and make the connections.

 Go to instance fixed menu or use shortcut key “I” from keypad to go instances
 Click on browse. This opens the library browser
 Now select the appropriate library for components like 
 Gpdk45 ------------------------nmos1v,  pmos1v
 Create Input and Output pins
 Make the connections by using fixed narrow wire key
 Click Check and Save button


![WhatsApp Image 2024-10-05 at 06 44 10_44041c73](https://github.com/user-attachments/assets/c2062a44-39ed-4e18-9250-0a51037476eb)



 


iii)Creating the Symbol for schematic Cell view:
•In the schematic window, execute 

 Create – Cell view – From Cell view
 The cell view from cell view window appears
 Check Lib Name, Cell Name, From View name must be schematic Press ok

•Now Symbol generation form appears. Click Ok If No changes required
•A new window with with default symbol is created.
•Edit the symbol if you want to give actual symbol shape else continue.
•Execute Create-Cell view-from cell view
•Library Name and Cell Name must be same which you have used for schematic. Press OK
•Check for the position of pin side.Prss OK
•Edit for the shape by Create-Shape-Choose required options to edit.


![WhatsApp Image 2024-10-05 at 06 44 09_c7305ee4](https://github.com/user-attachments/assets/7dafa89b-c94c-47a2-8158-317df26690a5)



iv)Creating the new test cell view:
•Go to CIW window, Execute File-New-Cell view
 Setup the new file form
 Library: Select the one you created.
 Cell: Cell name must be different from the name used in schematic cell view. Ex: Inverter_test
 View: Schematic
 Type: Schematic press OK
•Follow the step 3(ii) d to make the required connections


 ![WhatsApp Image 2024-10-05 at 06 44 09_99443789](https://github.com/user-attachments/assets/6e7318f8-7f0f-4656-b8e9-bafa00d2ace2)




Analog simulation by SPECTRE:
•In test cell view window
•Launch – ADE L(Analog Design Environment)
 Execute Setup—Simulation/directory/Host A new window opens
 Set the simulation window to spectre and click ok
 Execute Analysis – Choose. A window opens.
 Select the type and set the specifications and press OK
 Execute Output s—to be plotted – Select on Schematic
 Then Select the INPUT WIRE(Vin ) and OUTPUT WIRE(Vout) from your test Schematic using mouse
•Execute Simulation -- Net list and Run

 
 ![WhatsApp Image 2024-10-05 at 06 44 08_3488cbfa](https://github.com/user-attachments/assets/9b21ba7d-7300-4e61-8f63-c6e87720bc99)











**For Transient Analysis Settings and Output:**

 
 ![WhatsApp Image 2024-10-05 at 06 44 09_15d5f597](https://github.com/user-attachments/assets/a16c37ba-546a-4f8c-a295-09207b4ad159)


 
 ![WhatsApp Image 2024-10-05 at 06 44 10_c30502e6](https://github.com/user-attachments/assets/058ef747-5277-40cb-b72d-b29069984cd8)


**Results:**
1.The experiment successfully demonstrated the design and implementation of a 2:1 MUX using Cadence EDA tools. 
2.The successful verification through schematic, layout, and simulation underscores the effectiveness of using Cadence EDA tools for digital circuit design.
