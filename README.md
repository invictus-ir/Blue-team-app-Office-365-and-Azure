<h2>Blue-team-app-Office-365-and-Azure</h2>
The Blue team app for Office 365 and Azure is developed to help you investigate the Microsoft 365 Audit log. This app contains well over 20 unique searches that will help you identify suspicious activity in your Office 365 and Azure environment.

Requirements:
This app relies on the data collected in the Unified Audit Log.

There are several ways to export this data out of an environment:
1. Exporting the data using the Micrososft Extractor Suite (https://github.com/invictus-ir/Microsoft-Extractor-Suite)
2. Getting the data from the API which can be achieved with the Splunk Add-on for Microsoft Office 365 
3. Export the data using the Microsoft 365 Purview/Compliance portal. 

Dependencies:
The custom timeline app is used for one visualisation and can be found here:
https://splunkbase.splunk.com/app/3120

Getting started:
- Update the macro `ual` to the index where your UAL data is stored.

Important:
- Please send me feedback on the app so I can make it better!
- Follow @korstiaans and @InvictusIR to stay updated on the latest developments.

Credit to tr4cefl0w (https://twitter.com/tr4cefl0w) for some of the searches as described on his blog https://0x00sec.org/t/a-blue-team-guide-to-azure-office-365-monitoring/14411
