# GoKaronaGo
Desktop application to notify you personally when a vaccination session is available in your area.

Since the government announced that it is mandatory to book an appointment for a covid vaccine dose in prior, one has to really be quite lucky to grab a slot before another day turns into a houseful show. Thus the motivation for this app - which notifies you personally, within a minute of opening of a vaccinnation slot, meeting your predefined preferences.


<br>
Before you start - You will be notified on Telegram (a messaging app, available on all major platforms, find link in the post script section), so make sure you have the Telegram app on atleast one - your mobile or desktop. Please also read the Note at the end.
<br><br>

## WINDOWS
### Steps - 
1. Download/clone the  repository in a suitable directory on your computer.
2. Go to the 'Windows' directory in this downloaded/cloned repository and extract 'GoKaronaGo_windows.zip' file. 
3. Double-click the extracted file to run it. 
4. A GUI window will pop up. Fill in your preferences and hit 'Next' when done.
5. The app will provide you with a UniqueKey. Send this key, as a message, to the 'GoKaronaGo_bot' on telegram. On availability, you will be notified on the same phone number from which you sent the message.
6. On authentication success, click on 'Finish' button, but do not close the commnd prompt instance that started when you double-clicked. 


## LINUX
### Steps-
1. Download/clone the  repository in a suitable directory on your computer.
2. Go to the 'Linux' directory in this downloaded/cloned repository and extract the 'GoKaronaGo_linux.tar.gz' file.
3. Open terminal and make the directory, where you extracted, as present working directory. Then execute - 

```
./GoKaronaGo_linux
```
4. A GUI window will pop up. Fill in your preferences and hit 'Next' when done.
5. The app will provide you with a UniqueKey. Send this key, as a message, to the 'GoKaronaGo_bot' on telegram. On availability, you will be notified on the same phone number from which you sent the message.
6. On authentication success, click 'Finish' button, but do not close the terminal instance through which the script was executed. 

##### NOTE - 
A caveat here is that you need to keep your computer on until you get the notification. Otherwise the program will get killed, in which case you will need to refollow from Step 3 to bring the service up again. If your computer goes to sleep, the service will automatically restart once you login again, though it will be inactive while the computer is on sleep.

#### Post Script : 
Telegram on Google playstore - https://play.google.com/store/apps/details?id=org.telegram.messenger&hl=en_IN&gl=US
<br>
Telegram on Apple app store - https://apps.apple.com/in/app/telegram-messenger/id686449807
<br>
Telegram for Desktop - https://desktop.telegram.org/
