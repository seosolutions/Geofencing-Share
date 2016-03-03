# Geofencing-Share
Android application that trigger a notification when you enter a specific zone declared in json file, and the notification redirect you to a link.

#How to use 

Just modify the String var of the JSON file link on the main activity
Your JSON must suit this array <br>

{
	"client" : "FNAC Montparnasse",
	"link" : "https:\/\/www.FNAC.com",
	"produit" : "PC",
	"geofence" : {
		"lat" : "48.845905",
		"long" : "2.3250952",
		"radius" : "30"}
   }, 
