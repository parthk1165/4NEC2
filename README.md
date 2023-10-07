# 4NEC2 Tutorial: Simulation of Half Wave Dipole Antenna 
4NEC2 is a software tool primarily used for the design and analysis of antennas and other electromagnetic systems.

## Steps to Download 
1. Go to the official 4NEC2 website. ( http://www.qsl.net/4nec2/ ) 
2. Navigate to the "Downloads" section of the website.
3. Look for the appropriate version of the software for your operating system (Windows, macOS, or Linux) and click on the download link.
4. Once the download is complete, locate the downloaded file on your computer.
5. Run the installer and follow the on-screen instructions to install the software.
6. After the installation is complete, launch the 4NEC2 software.
## Steps to Simulation of Half Wave Dipole Antenna 

Steps to use 4NEC2 software to simulate half wave dipole antenna at 2.4GHz:

Step 1 : Launch the 4NEC2 software.
<!---
![Untitled](https://github.com/parthk1165/TicTacToe/assets/145101202/427d0dd8-b0ba-43a4-bd5b-a85a85a2e66a)
-->
<img src="https://github.com/parthk1165/TicTacToe/assets/145101202/427d0dd8-b0ba-43a4-bd5b-a85a85a2e66a" width="392" height="625.6" />

Step 2 : Create a new project: In the toolbar menu, select "File" and choose "New" to create a new project

Step 3 : In Setting , Click on geometry edit  
<!--
![Untitled 1](https://github.com/parthk1165/TicTacToe/assets/145101202/f1ffc9c9-2626-4352-ad40-b00232f8a8a2)
-->
<img src="https://github.com/parthk1165/TicTacToe/assets/145101202/f1ffc9c9-2626-4352-ad40-b00232f8a8a2" width="392  " height="625.6" />

Step 4 : Click on Edit NEC - input filed , a new window pops up 
<!--
![Untitled 2](https://github.com/parthk1165/4NEC2/assets/145101202/6f78a3cb-705d-459d-be47-917289acef1f)
-->

<img src="https://github.com/parthk1165/4NEC2/assets/145101202/6f78a3cb-705d-459d-be47-917289acef1f" width="392  " height="625.6" />

Step 5 : Create a new project 

![Untitled 3](https://github.com/parthk1165/4NEC2/assets/145101202/4a234312-29a4-4828-9847-51c2d7b39090)



Step 6 : Set the frequency of the simulation to 2.4GHz

![Untitled 4](https://github.com/parthk1165/4NEC2/assets/145101202/c340beeb-6ce8-4cf2-9ed4-c9519e5e9524)

Step 7 : Click on Wire geometry to create a wire 

![Untitled 5](https://github.com/parthk1165/4NEC2/assets/145101202/01d7ccfa-18eb-4602-a7f9-6ff46dd62173)


Step 8 : Select the "Add New objects " option from the toolbar and add the wire on the z-axis.

![Untitled 6](https://github.com/parthk1165/4NEC2/assets/145101202/e8439f68-9b43-4237-88d1-b48586fb31ff)

Step 9 : Set wire radius to be 0.5 mm 

![Untitled 7](https://github.com/parthk1165/4NEC2/assets/145101202/e73e995a-448a-40a3-9a50-8d615c569c2d)


Step 10 : Set the parameters of the wire 
1. Set the z parameter of the End-1 (mtr) to 0.031225 and -0.031225 
( Specifying the start and end points of the dipole, which should be half a wavelength apart )
2. Set the seg to 100

![Untitled 8](https://github.com/parthk1165/4NEC2/assets/145101202/e7ad5dfb-4c51-4cd6-89b7-ff9f75eb5bf5)



Step 11 : Add V/I source similar to wire and place it on the origin

![Untitled 9](https://github.com/parthk1165/4NEC2/assets/145101202/dca649ce-9309-4c51-a026-084133d2b071)
![Untitled 10](https://github.com/parthk1165/4NEC2/assets/145101202/3f97f253-a3f4-438a-a176-02991e1c1590)


Step 12 : Click on Run NEC and wait for the results to be calculated.

![Untitled 11](https://github.com/parthk1165/4NEC2/assets/145101202/d71ec013-f8a9-4e7a-8cb9-a659fa4e9568)


Step 13 : Click on Frequency sweep and Configure the simulation settings, such as start , stop and step 
<!--
![Untitled 12](https://github.com/parthk1165/4NEC2/assets/145101202/661f2a12-4c75-4978-9402-dba27cadf268)
-->

<img src="https://github.com/parthk1165/4NEC2/assets/145101202/661f2a12-4c75-4978-9402-dba27cadf268" width="333.6" height="542.4" />

Step 14 : Run the simulation and wait for the results to be calculated.

Step 15 : The software provides various graphs, charts, and numerical data, 
              including radiation pattern plots, gain, input impedance, and SWR.
              Analyze the simulation results, which include Bandwidth , HPBW 

![Untitled 13](https://github.com/parthk1165/4NEC2/assets/145101202/af2d3465-68b5-44a3-8a8b-af94162814ea)


Bandwidth

<!--
![Untitled 14](https://github.com/parthk1165/4NEC2/assets/145101202/88137155-7e98-408c-a4e1-db5018e1b12c)
-->
<img src="https://github.com/parthk1165/4NEC2/assets/145101202/88137155-7e98-408c-a4e1-db5018e1b12c" width="296" height="334.5" />


HPBW

<!--
![Untitled 15](https://github.com/parthk1165/4NEC2/assets/145101202/b576e54e-a43f-46ff-95fe-3f77376fc19a)
-->
<img src="https://github.com/parthk1165/4NEC2/assets/145101202/b576e54e-a43f-46ff-95fe-3f77376fc19a" width="392" height="625.6" />



Step 16 : To view the antenna in 3D , click on the “3D” button
<!--

![Untitled 16](https://github.com/parthk1165/4NEC2/assets/145101202/e7196691-0a72-4566-8526-b64139c89492)
-->

<img src="https://github.com/parthk1165/4NEC2/assets/145101202/e7196691-0a72-4566-8526-b64139c89492" width="392" height="625.6" />

Step 17 : To see the impedance, click on "Multi-color”

![Untitled 17](https://github.com/parthk1165/4NEC2/assets/145101202/919bcf79-b38c-4edd-96d3-52f0a48d566e)
![Untitled 18](https://github.com/parthk1165/4NEC2/assets/145101202/a55444ad-6a88-4a5c-abae-86938c0ceef7)



Step 18 : Repeat the simulation and analysis steps until satisfactory results are obtained.

Step 19 : Save the project and document the findings and conclusions. 

Step 20 : Export the plots, graphs, and other relevant data for documentation or further analysis

Remember to consult the 4NEC2 documentation or online resources for more detailed instructions and troubleshooting tips.
