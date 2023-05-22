# Google_calendar_API_automation
JS program which returns array of busy intervals in a given time period for  any shared Google calendar. Input: shared Google calendar ID; time period (starting and ending  moments). Output : busy intervals. in a table

Refer to the following links to enable Calendar API and get the credentials:
[JavaScript quickstart](https://developers.google.com/calendar/quickstart/js)


Replace the following:

- YOUR_CLIENT_ID: the client ID that you created when you authorized credentials for a web application.
- YOUR_API_KEY: the API key that you created as a Prerequisite.


1. In your working directory, install the http-server package:
```
npm install http-server 
```
2. In your working directory, start a web server:
```
npx http-server -p 8000
```