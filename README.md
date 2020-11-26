# Microsoft Power Automate - AutomatischeReistijd

This Power Automate flow will calculate your travel time.
For each appointment in your Office 365 calendar the Power Automate flow will take the location of it, and calculate the travel time between that and your home location.
After the travel time has been calculated, the Power Automate flow will create a new appointment in your calendar with the duration of the travel time (+15min).

_The flow won't be triggerd for Microsoft Teams meetings._

## Connections in use
* Bing Maps
* Notifications
* Office 365 Outlook

## Setup
1. Please download the Automatischereistijd.zip.
2. Go to https://emea.flow.microsoft.com/manage/flows/import.
3. Upload and import the Automatischereistijd.zip file.
4. Open the Power Automate flow and change the calendar id to the desired calendar (need's to be done in 2 locations).
5. Set your home location in 'StartLocaion'.
6. Save.
