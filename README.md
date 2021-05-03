# GoKaronaGo
Linux application to notify you personally when a vaccination session is available in your area.

Since the government announced that it is mandatory to book an appointement for a covid vaccine dose in prior, one has to really be quite lucky to grab a slot before another day turns into a houseful show. Thus the motivation for this app - which notifies you personally, within a minute of opening of a vaccinnation slot, meeting your predefined preferences.


Right now only linux executable is available. Will soon update with Windows executable.

<br>
Before you start - You will be notified on Telegram, so make sure you have the Telegram app on atleast one - your mobile or desktop.
<br><br>

## Steps

1. Download the executable file 'GoKaronaGo_linux' from the repository and save it in a suitable directory on your computer.
2. cd to the directory and with it as the present working directory, execute - 

```
./GoKaronaGo_linux
```
3. A GUI window will pop up. Fill in your preferences and hit 'Next' when done.
4. The app will provide you with a UniqueKey. Send this key, as a message, to the 'GoKaronaGo_bot' on telegram. On availability, you will be notified on the same phone number from which you sent the message.
5. On authentication success, close the GUI window but do not close the terminal instance through which the script was executed. 

##### NOTE - 
One caveat here is that you need to keep your computer on (prevent sleep too, yeah!) until you do not get the notification. Otherwise the program will get killed, in which case you will need to refollow from Step 2 to bring the service up again.
