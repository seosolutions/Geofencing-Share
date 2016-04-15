# Geofencing-Share
Android application that trigger a notification when you enter a specific zone declared in json file, and the notification redirect you to a link.

#How to use 

Just modify the String var of the JSON file link on the main activity after the upload<br>
Your JSON must suit this array <br>

{
	"client" : "FNAC Montparnasse",<br>
	"link" : "https:\/\/www.FNAC.com",<br>
	"produit" : "PC",<br>
	"geofence" : {<br>
		"lat" : "48.845905",<br>
		"long" : "2.3250952",<br>
		"radius" : "30"}<br>
   }, <br>
   
   
