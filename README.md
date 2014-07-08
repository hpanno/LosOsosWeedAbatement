LosOsosWeedAbatement
====================

######Los Osos Weed Abatement PDFMap Links:
---

https://dl.dropboxusercontent.com/u/151188090/LosOsosWeedAbatement.pdf 
https://dl.dropboxusercontent.com/u/38388156/15weeds_east.pdf 
https://dl.dropboxusercontent.com/u/38388156/15weeds_north.pdf

######PDFMaps
---

Download the [PDFMapsApp](http://www.avenza.com/pdf-maps) for your iPhone or Andriod device.

<b>Uploading PDF Map to App</b> 
<br>Select '+' 
<br>Type/Paste link from above into URL field


<b>Dropping Points and Adding Photos</b> 
<br>Zoom to the property in question 
<br>Make sure the center 'dial' sits in the middle of the parcel 
<br>Drop the pin 
<br>Select the 'i' next to the Placemark you just created 
<br>'Photos' 
<br>'+' 
<br>Take a photo 
<br>[you can leave the default placemark name] 
<br>You can enter in a Description as you see fit 
<br>Go back to Map


<b>Exporting Data</b> 
<br>Select the 'Map Features' icon 
<br>Select 'Export' 
<br>'Export Data (KML/GPX)' 
<br>File: leave default 'LosOsosWeedAbatement'+[_INITIALS] 
i.e. LosOsosWeedAbatement_HP 
<br>Select 'KML' 
<br>Export to: 'Mail' 
<br>Select: 'Export' 
<br>Select: 'Orignial Size' 
<br>Select: 'Export' 
<br>To: my email

######Working with the data
--- 
Import each kml into QGIS and save as a .shp. 
Import all data into Arc and merge to one file. 
Perform a join from the points to the parcel layer. 
Make sure that it is looking for the parcel in which the point sits. 
Select the following fields:

		APN, APN-9, OWNER, ADDRESS-1, CITY, STATE, ZIP, PLUS_4, SITUS_1, STREET_1, TYPE_1
  
Using X Tools Pro: table operations> export table as MSWord Doc. The table will open automatically in MSword. Select the APN column; in the 'Home' ribbon select 'Conditional Formatting'; 'Highlight cell rules'; 'duplicate' --> go through and confirm/validate these duplicates; delete any duplicated entires.


######In GoogleEarth 
---
Drag all KMLs into 'Temporary Places' in Google Earth, Right click the Temporary Places folder and select  save place as. Send this KMZ to executive secretary.
