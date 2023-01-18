## Prerequisite

* Before Running the **MainBot**, Configure the variable {vConfigLocation} in the **Converter bot** To the location of the excel file in the PDF2IMG/config.xlsx.
## Dependencies
   PyMuPDF==1.16.7 
* Install "PyMuPDF==1.16.7" in the "Rocketbot/modules/libs" folder with this command 
``` pip install PyMuPDF==1.16.7 -t ./ ```
* Note: Use python 3.6.8 32bit version as Rocketbot runs on this python version.


## Properties in the Excel.
| Property                          | Description                                               |
| --------------------------------- | --------------------------------------------------------- |
| pdf.folder.location               | The pdf files input location.                             |
| pdf.folder.scan.interval          | The time interval in seconds.                             |
| img.email.destinations	          | The destination for the compressed zip to be sent.        |
| img.converted.destination	        | The output of the converted pdf location.                 |
| img.folders.archived.location	    | the Location for the archived converted folders location. |


* Refer the Swimlane diagram given below for more information about the bot flow. 
![swimlanes-ad26c5e17206114a376f724862df8eb3](https://user-images.githubusercontent.com/108778720/213090852-23e48d6f-a730-46a2-965f-ea3f211377f4.png)
