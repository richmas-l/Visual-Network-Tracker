<h1>Visual Network Tracker</h1>

<h2>Description</h2>
The project entails a Python script that guides users through an immersive visual representation of their network traffic on Google Maps. This visualization is achieved by extracting data from Wireshark and incorporating it into the program for generating the final representation.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Python3</b> 
- <b>Wireshark</b>
- <b>Google maps</b>
- <b>Geolitecity database</b>

<h2>Environments Used </h2>

- <b>Kali linux</b> 

<h2>Setup</h2>

- <b>Create a new depository and save this .py script inside</b> 
- <b>download Geolitecity database into the depository</b> 

<h2>Program walk-through:</h2>

<p align="center">
Start Wireshark<br/>
<img src="https://imgur.com/FGAFF5I.png" height="80%" width="80%"
<br />
<br />
 
<p align="center">  
Stop Wireshark once complete with your internet browsing  <br/>
  Save the packets in pcap format into the newly created depository, take note of the filename.
<img src="https://imgur.com/DvmAQXH.png" height="80%" width="80%">
<br />
<br />
  
<p align="center">  
Open the script <br/>
  Rename the pcap file on line 8 to the filename of your pcap file in previous step.<br/>
    Input your ip address on line 37
  Save the script
<img src="https://imgur.com/e8gVshF.png" height="80%" width="80%">
<br />
<br />
  
<p align="center">  
Run the script & save the output onto a new file<br/>
  Save the file in .kml format.<br/>
    you can manually run script and copy the contents or run the command below
<img src="https://imgur.com/Z5iCwOA.png" height="80%" width="80%">
<br />
<br />

<p align="center">  
Open Google Maps <br/>
 Import the kml file you saved in the previous step.<br/>
<img src="https://imgur.com/mcCmac1.png" height="80%" width="80%">
<br />
<br />

<p align="center">  
Results<br/>
 your final results will show traffic from your specific location.<br/>
<img src="https://imgur.com/JEE4qWp.png" height="80%" width="80%">
<br />
<br />
  

<h2>Resources & References</h2>
 - [Vinslov Academy](https://vinsloev.com/#/)
 - [GeoliteCity](https://mbcc2006/GeoLiteCity-data)
 - [Google Developers](https://developers.google.com/kml)
