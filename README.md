<h1>UAV-SolidWorks</h1>



<h2>Description</h2>
Companies are currently designing and iterating on weight-shift control concepts to develop Unmanned Aerial Vehicles (UAVs) ; this kind of controller shifts the center of mass of the aircraft to produce changes in pitch and bank. This project aimed to design an e-UAV prototype with a dual pusher trust propulsion, an entirely electric system, and the design of the airframe, fuselage, and wing. Additionally, a variable payload, with a maximum of 4 battery cases, and two main bodies separated from each other easy to assemble and disassemble were considered. The aircraft was optimized for a maximum take-off weight of 25kg.  
<br />
<p align="center">
<img src="https://i.imgur.com/NA47IWg.png" height="40%" width="40%" alt="UAV assembly"/>
</p>

<h2>Software Used</h2>

- <b>SolidWorks</b>
- <b>Matlab</b>


<h2>Directory structure:</h2>

The project is divided into 4 sub-assemblies:  <br/>
- <b>1-Wing</b>
- <b>2-Frame</b>
- <b>3-Landing Gear</b>
- <b>4- Cargo bay</b>

Each sub-assembly is located inside a folder with the same name. These folders contain all the parts required for the sub-assembly as well as an "equations.txt" file that contains all the global variables used for modeling the parts. The sub-assembly files are named "Xassembly.SLDASM" where X is the name of the specific sub-assembly, these are only SLDASM files located at the top level of the folder, if additional sub-assembluies where required, they were placed inside a folder named "additional sub-assemblies. </b>

The main assembly is located inside a folder named "0-Main". This file is named "mainAssembly.SLDASM".


<h2>ScreenShots:</h2>

<p align="center">
Wing structure: <br/>
<img src="https://i.imgur.com/71QAYeG.png" height="60%" width="60%" alt="WingStructure"/>
<br />
<br />
Frame:  <br/>
<img src="https://i.imgur.com/UkeBQuC.png" height="40%" width="40%" alt="Frame"/>
<br />
<br />
Frame-wing connection: <br/>
<img src="https://i.imgur.com/yQ8jmMf.png" height="80%" width="80%" alt="Wing-Frame-Connection"/>
<br />
<br />
Landing Gear:  <br/>
<img src="https://i.imgur.com/OngoyvI.png" height="60%" width="60%" alt="LandingGear"/>
<br />
<img src="https://i.imgur.com/RIbs40e.png" height="40%" width="40%" alt="LandingGear2"/>
<br />
<br />
