### Package Parsing Error (Android)
This is a pretty uncommon error when installing an APK on your phone.  
Fortunately, there are various methods to get this fixed, but it could be a bit time consuming if one of those don't work.

#### Option 1: Automatic APK Fix through "ps!fixapk"
Rarely our server can bug during the APK creation process and eventually corrupt the APK.  
Running the `ps!fixapk` command in the **#gdps-creator-commands** channel will force a re-creation of the APK for your GDPS.  
This should work out most of the time.

#### Option 2: Manually fixing the APK by editing its installation location
[This video is a pretty easy-to-follow tutorial that helps fixing the parsing error. You should give it a watch.](https://www.youtube.com/watch?v=d0Lh0XCZyjQ)  
If this didn't work out, you might want to follow the steps below then.

#### Option 3: Use an APK installer from the Playstore
As stupid as it sounds, this might work out for you.  
There are various APK installers on store, though some of them just plain redirect you to the package installer.  
[From our testing, this one works so far.](https://play.google.com/store/apps/details?id=com.apkinstaller.ApkInstaller)

#### Option 4: Resetting your GDPS and choose a different name
If you made a fresh GDPS you'll most likely be able to simply delete it and make a new one.  
For some odd reason, the name of the GDPS can corrupt the APK.  
The only occurance that it can ***guaranteed*** break the APK is by starting the GDPS name using a digit, please avoid that.  
We don't know why this happens but we are unable to check if it works right away before creating your GDPS.  
Once you ran the `ps!delete` command in the **#gdps-creator-commands** channel, you will have to re-create your GDPS.  
Please make sure to choose a different name, it might even work out if you change only 1 character!
