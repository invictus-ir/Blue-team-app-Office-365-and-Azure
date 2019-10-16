# Blue-team-app-Office-365-and-Azure
The Blue team app for Office 365 and Azure is developed to help you investigate the Office 365 Audit log. This app contains over 20 unique searches that will help you identify suspicious activity in your Office 365 and Azure environment.

Requirements:
This app relies on the data collected in the Unified Audit Log.

There are several ways to export this data out of an environment:
1. Exporting the data using the Office 365 Extractor (https://github.com/PwC-IR/Office-365-Extractor)
2. Getting the data from the API which can be achieved with the Splunk Add-on for Microsoft Office 365
3. Using the Office 365 Security and Compliance web portal

Dependencies:
The custom timeline app is used for one visualisation and can be found here:
https://splunkbase.splunk.com/app/3120

Getting started:
- Update the macro `ual` to the index where your UAL data is stored.

Important:
- Please send me feedback on the app so I can make it better!

Credit to tr4cefl0w (https://twitter.com/tr4cefl0w) for some of the searches as described on his blog https://0x00sec.org/t/a-blue-team-guide-to-azure-office-365-monitoring/14411
