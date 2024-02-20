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

HTML file to display Google Sheet content in OBS [local HTML file](https://github.com/UUoocl/Timer-Web-App/blob/main/localIndex.html)

OBS -->[OBS project](https://obsproject.com/)

[Zoom.us](https://zoom.us/)

# Share The Google Sheet and Google Script

## The Google Sheet will need to be shared. 
Click the Share button
  
<img width="141" alt="image" src="https://github.com/UUoocl/Timer-Web-App/assets/99063397/f6d37c2b-3f75-42b8-a90c-67125bc25c25">

- 
<img width="506" alt="image" src="https://github.com/UUoocl/Timer-Web-App/assets/99063397/d0d3ac97-0c67-458c-a10a-27185b552883">

## Deploy the Google Apps Script as a Web App
The App script can be found by navigating to the Extensions-->Apps Script

<img width="146" alt="image" src="https://github.com/UUoocl/Timer-Web-App/assets/99063397/1adeb390-8b2e-4db8-a4d7-dcbbcefd3843">

Click Deploy --> New Deployment

<img width="202" alt="image" src="https://github.com/UUoocl/Timer-Web-App/assets/99063397/7003f484-51b4-49f4-a5af-db43620bbc12">

-

<img width="745" alt="image" src="https://github.com/UUoocl/Timer-Web-App/assets/99063397/356ba775-a84e-49b7-b879-4a0316114e9d">



