# 4NEC2 Tutorial: Simulation of Half Wave Dipole Antenna 
4nec2 is a software tool primarily used for the design and analysis of antennas and other electromagnetic systems.

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

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/6b0ba1f8-4dff-4058-9868-5f61e9681358/0d18751a-e5fa-4a83-8f97-a079a61881eb/Untitled.png)

Step 2 : Create a new project: In the toolbar menu, select "File" and choose "New" to create a new project

Step 3 : In Setting , Click on geometry edit  

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/6b0ba1f8-4dff-4058-9868-5f61e9681358/9b628bc7-c64a-4981-a368-1cff4488cc95/Untitled.png)

Step 4 : Click on Edit NEC - input filed , a new window pops up 

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/6b0ba1f8-4dff-4058-9868-5f61e9681358/edf84b54-e6d5-4a1f-9f3b-1feaf39982d9/Untitled.png)

Step 5 : Create a new project 

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/6b0ba1f8-4dff-4058-9868-5f61e9681358/118ee27e-0912-4ac6-87fd-9fe18224acb5/Untitled.png)

Step 6 : Set the frequency of the simulation to 2.4GHz

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/6b0ba1f8-4dff-4058-9868-5f61e9681358/0c530d41-90a0-41ab-a340-7001371f0d6a/Untitled.png)

Step 7 : Click on Wire geometry to create a wire 

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/6b0ba1f8-4dff-4058-9868-5f61e9681358/8ab3f1f5-dafb-4c46-aaf1-9d5bdf891352/Untitled.png)

Step 8 : Select the "Add New objects " option from the toolbar and add the wire on the z-axis.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/6b0ba1f8-4dff-4058-9868-5f61e9681358/24e99106-1ff3-4dd6-b298-e0fc4ba94bf5/Untitled.png)

Step 9 : Set wire radius to be 0.5 mm 

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/6b0ba1f8-4dff-4058-9868-5f61e9681358/ea7855ed-44d0-4e2c-b147-c4587ea97673/Untitled.png)

Step 10 : Set the parameters of the wire 
1. Set the z parameter of the End-1 (mtr) to 0.031225 and -0.031225 
( Specifying the start and end points of the dipole, which should be half a wavelength apart )
2. Set the seg to 100 

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/6b0ba1f8-4dff-4058-9868-5f61e9681358/60e93908-5e6d-4844-8cd7-2a9f08b291e9/Untitled.png)

Step 11 : Add V/I source similar to wire and place it on the origin

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/6b0ba1f8-4dff-4058-9868-5f61e9681358/582ec017-2973-4b63-8cc3-108af27e32ad/Untitled.png)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/6b0ba1f8-4dff-4058-9868-5f61e9681358/3c6753a9-aa4e-4e37-ad85-2b3bd0e593a9/Untitled.png)

Step 12 : Click on Run NEC and wait for the results to be calculated.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/6b0ba1f8-4dff-4058-9868-5f61e9681358/5780c2a9-3319-46d8-8f66-f61d5cebb3d2/Untitled.png)

Step 13 : Click on Frequency sweep and Configure the simulation settings, such as start , stop and step 

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/6b0ba1f8-4dff-4058-9868-5f61e9681358/287bc0b0-2e9d-4b96-b4aa-e003a8376f1c/Untitled.png)

Step 14 : Run the simulation and wait for the results to be calculated.

Step 15 : The software provides various graphs, charts, and numerical data, 
              including radiation pattern plots, gain, input impedance, and SWR.
              Analyze the simulation results, which include Bandwidth , HPBW 

![Bandwidth](https://prod-files-secure.s3.us-west-2.amazonaws.com/6b0ba1f8-4dff-4058-9868-5f61e9681358/4b7cd824-6580-415e-96de-01b6cb08e449/Untitled.png)

Bandwidth

![HPBW](https://prod-files-secure.s3.us-west-2.amazonaws.com/6b0ba1f8-4dff-4058-9868-5f61e9681358/61014746-e767-49a0-9a03-762733a20304/Untitled.png)

HPBW

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/6b0ba1f8-4dff-4058-9868-5f61e9681358/9bcc9ce6-fc55-4744-888f-f1f8e69a494a/Untitled.png)

Step 16 : To view the antenna in 3D , click on the “3D” button

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/6b0ba1f8-4dff-4058-9868-5f61e9681358/0986c4b0-aa7a-4c68-b157-58318b2be6d8/Untitled.png)

Step 17 : To see the impedance, click on "Multi-color”

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/6b0ba1f8-4dff-4058-9868-5f61e9681358/39386747-73ba-4281-9233-22406a7a7691/Untitled.png)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/6b0ba1f8-4dff-4058-9868-5f61e9681358/84d33da4-2c17-4ed8-ab08-1881776d6072/Untitled.png)

Step 18 : Repeat the simulation and analysis steps until satisfactory results are obtained.

Step 19 : Save the project and document the findings and conclusions. 

Step 20 : Export the plots, graphs, and other relevant data for documentation or further analysis

Remember to consult the 4NEC2 documentation or online resources for more detailed instructions and troubleshooting tips.
