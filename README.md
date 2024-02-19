# Meeting-Timer-Web-App
An example of combining tools to record meeting details. Tools used in this process are Google Sheets, Google Application Script, local HTML, OBS and Zoom.

```mermaid
graph TD;
    GoogleSheets-->GAS;
    GAS-->GoogleSheets;
GAS-->WebApp;
WebApp-->GAS;
GoogleSheets-->LocalHTML;
    LocalHTML-->OBS;
    OBS-->Zoom;
```

# Setup
Google Sheet with Google App Script--> [Copy Google Sheet and script for the Timer App](https://docs.google.com/spreadsheets/d/1YbaUzI7DMh1Orqz31gqL0c4pw2PeIC1uXLST0YoQpbw/copy)

HTML file to display Google Sheet content in 

OBS -->[OBS project](https://obsproject.com/)

[Zoom.us](https://zoom.us/)




