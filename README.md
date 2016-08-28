#Amazon FireTV Stick Loader

###FREE YOUR FIRESTICK!!!

####firepwn.com

<br/>

####Scripting To Root, Downgrade, Load Apps and Settings Onto Amazon FireTV and FireStick

<br/>

![Menu Preview 1](https://github.com/esc0rtd3w/firestick-loader/blob/master/misc/preview/options-main.png)
<br/><br/>
![Menu Preview 2](https://github.com/esc0rtd3w/firestick-loader/blob/master/misc/preview/options-tweaks.png)

<br/>

***Known Issues:***

- Currently Does Not Have Rooting Support For FireOS 5.2.1.1.

- If KingRoot is left installed, Kodi will have playback issues (Unknown Reason. Use "unroot" option to remove KingRoot after all root required actions are taken.)
<br/><br/>

	
***Current Project Testing Status:***

- 275MB+ Available Free Memory Running From HOME Screen

- Blue Stock FireTV Stick Boot Animation

- FireStopper Installed Into "/system/app/FireStopper/" (Factory Reset Leaves Launcher In Tact)

- Amazon HOME Menu Completely Stripped Functionality* (Apps, Search, and Settings Still Show Items)

    * During a Factory Reset, You Will Be Brought To The Amazon HOME Menu Briefly, Then FireStopper Will Load

    * Running The Disable Amazon Bloat Script After Factory Reset Will Also Stop Amazon HOME Menu From Loading Completely

- Amazon Settings Menu Available (Parental Controls, Help, and My Account DISABLED)

- Amazon Shopping, Amazon Underground, and Amazon Video Are Working Installed As Uninstallable User Apps

    * Amazon Prime Features Are Currently Working Using Amazon Video and Shopping Apps

- Amazon FireTV Remote App Still Supported

- Amazon Voice Remote Still Supported

- Hold HOME Button Function To Sleep Available
<br/><br/>


***Preview Finished Setup Using "root-stick.cmd" Automatic Option***
######\*\* Can also manually use Install, Root, Downgrade (if higher than 5.0.5), Busybox, and Debloat/Remove/Adblock Options \*\*

![Finished Preview Clean](https://github.com/esc0rtd3w/firestick-loader/blob/master/misc/preview/home/home-firestopper-system-clean.jpg)
<br/><br/>


***Preview Finished Setup Using "root-stick.cmd" and "install-apps-lite-auto.cmd"***

![Finished Preview Loaded](https://github.com/esc0rtd3w/firestick-loader/blob/master/misc/preview/home/home-loaded-standard.jpg)
<br/><br/>


***Preview Custom FireStarter Build***
######\*\* Based off original FireStopper Port (https://github.com/jkchr1s/FireStarter) \*\*
######\*\* Which Is Based off original FireStarter \[Now AppStarter\] (https://github.com/sphinx02/AppStarter) \*\*

![Finished Preview Loaded](https://github.com/esc0rtd3w/firestick-loader/blob/master/misc/preview/home/home-firestarter-mod-system.jpg)
<br/><br/>

![Finished Preview Loaded](https://github.com/esc0rtd3w/firestick-loader/blob/master/misc/preview/home/home-firestarter-mod-settings.jpg)
<br/><br/><br/>


***Menu Options:***

- **Automatic Mode**

    - Automatically Continues To The Next Step (some intervention required)
	- Has a Menu Option To Add Downgrade To The Task List

- **Rooting Options**

    - Install KingRoot
	- Root Device (Automatically Does All The Steps To Get Full Root)
	- Issue "su" Request To Device (Useful for triggering Deny/Allow prompt)

- **Downgrade Firmware** \****ROOT REQUIRED***\*

    - Currently 5.0.5 Is The Only Downgrade Version Available
	- Automatically Extracts, Pushes, Moves, Creates Recovery Config File and Reboots To Install

- **Install Busybox** \****ROOT REQUIRED***\*

    - GUI Install (Automatically Does All The Work To Click Everything, Install, and Remove APK After)
	- Has a Terminal Version That Uses a Shell Script

- **Disable Amazon Bloat** \****ROOT REQUIRED***\*

    - Disable Only Menu Option
    - Disable and Safe Remove Menu Option
    - Disable, Safe Remove, and Ad Block Menu Option

- **Clear All Caches** \****ROOT REQUIRED***\*

    - /cache/
    - /cache/dalvik-cache/
    - /data/dalvik-cache/

- **Clean SD Card and Kodi Data**

    - Option To Erase All Kodi Data From /sdcard/
    - Option To Erase The Entire /sdcard/ Partition

- **Factory Reset**

    - User Mode Factory Reset (Automatically Loads The Activity and Clicks OK)
    - Root Mode Factory Reset (Removes Everything In /data/ That Is Safe and Saves Configuration Files)

- **Unroot** \****ROOT REQUIRED***\*

    - Removes KingRoot (Has a Bluetooth Mouse Option and TeamViewer Option)
	- Bluetooth Mouse Option Lets You Use a Mouse To Navigate
	- TeamViewer Option Launches TeamViewer on PC and Android To Give Mouse Control

- **Fixes, Tweaks, and Misc**

    - Contains Boot Animation, Disable Ads, Launch Apps, Allow SU Requests, and Other Misc Fixes and Tweaks

- **Directly Invoke Amazon Settings Menu Items**

    - Open Common Amazon Settings Menus Directly Through ADB Shell
	
<br/><br/>
	
	
- **List of Amazon Bloat Removed (Tested Safe and With No Errors or Issues Using Scripting)**
	
    - /system/app/DeviceControlService/
    - /system/app/DocumentsUI/
    - /system/app/fdrw/
    - /system/app/PicoTts/
    - /system/app/UnifiedSettingsProvider/
    - /system/app/WebCryptoTZService/
    - /system/app/WhiteListedUrlProvider/
	
    - /system/priv-app/amazon.jackson-19/
    - /system/priv-app/AmazonKKWebViewLib/
    - /system/priv-app/AmazonNetworkMonitor/
    - /system/priv-app/BackupRestoreConfirmation/
    - /system/priv-app/com.amazon.ags.app/
    - /system/priv-app/com.amazon.avod/
    - /system/priv-app/com.amazon.bueller.music/
    - /system/priv-app/com.amazon.communication/
    - /system/priv-app/com.amazon.communication.discovery/
    - /system/priv-app/com.amazon.device.sync/
    - /system/priv-app/com.amazon.device.sync.sdk.internal/
    - /system/priv-app/com.amazon.identity.auth.device.authorization/
    - /system/priv-app/com.amazon.imp/
    - /system/priv-app/com.amazon.kindle.cms-service/
    - /system/priv-app/com.amazon.kindle.devicecontrols/
    - /system/priv-app/com.amazon.kso.blackbird/
    - /system/priv-app/com.amazon.ods.kindleconnect/
    - /system/priv-app/com.amazon.parentalcontrols/
    - /system/priv-app/com.amazon.precog/
    - /system/priv-app/com.amazon.securitysyncclient/
    - /system/priv-app/com.amazon.sharingservice.android.client.proxy.release/
    - /system/priv-app/com.amazon.shoptv.client/
    - /system/priv-app/com.amazon.tcomm/
    - /system/priv-app/com.amazon.tmm.tutorial/
    - /system/priv-app/com.amazon.tv.aiv.support/
    - /system/priv-app/com.amazon.tv.csapp/
    - /system/priv-app/com.amazon.tv.legal.notices/
    - /system/priv-app/com.amazon.tv.oobe/
    - /system/priv-app/com.amazon.tv.parentalcontrols/
    - /system/priv-app/com.amazon.venezia/
    - /system/priv-app/com.amazon.videoads.app/
    - /system/priv-app/com.amazon.visualonawv/
    - /system/priv-app/ContentSupportProvider/
    - /system/priv-app/CrashManager/
    - /system/priv-app/DeviceClientPlatformContractsFramework/
    - /system/priv-app/DeviceMessagingAndroid/
    - /system/priv-app/DeviceMessagingAndroidInternalSDK/
    - /system/priv-app/DeviceMessagingAndroidSDK/
    - /system/priv-app/DeviceSoftwareOTA/
    - /system/priv-app/DeviceSoftwareOTAIdleOverride/
    - /system/priv-app/DownloadProvider/
    - /system/priv-app/FireApplicationCompatibilityEnforcer/
    - /system/priv-app/FireApplicationCompatibilityEnforcerSDK/
    - /system/priv-app/FireOsMiddlewareDebugApp/
    - /system/priv-app/FireRecessProxy/
    - /system/priv-app/FireTVDefaultMediaReceiver/
    - /system/priv-app/FireTvNotificationService/
    - /system/priv-app/FireTVSystemUI/
    - /system/priv-app/FusedLocation/
    - /system/priv-app/LogManager/
    - /system/priv-app/ManagedProvisioning/
    - /system/priv-app/marketplace_service_receiver/
    - /system/priv-app/shipmode/
    - /system/priv-app/sync-provider_ipc-release/
    - /system/priv-app/sync-service-fireos-release/
    - /system/priv-app/SystemUpdatesUI/
    - /system/priv-app/UnifiedShareActivityChooser/
    - /system/priv-app/WallpaperCropper/
    
	- /system/framework/android.amazon.perm/
	
<br/><br/>	

**Untested Bloat From FireOS 5.2.1.1**
    - rm -r /system/priv-app/com.amazon.tv.nimh
    - rm -r /system/priv-app/AdvertisingIdSettings
    - rm -r /system/priv-app/FireTvSaleService
    - rm -r /system/priv-app/IvonaTTS
    - rm -r /system/priv-app/IvonaTtsOrchestrator
    - rm -r /system/priv-app/Logan
    - rm -r /system/priv-app/TvProvider

<br/><br/>
	
**List of Amazon Bloat Left Alone**

- Screensaver Config
    - /system/priv-app/com.amazon.bueller.photos/

- Amazon Remote Android App
    - /system/priv-app/com.amazon.storm.lightning.services/
    - /system/priv-app/com.amazon.storm.lightning.tutorial/
    - /system/priv-app/WhisperlinkSdk/
    - /system/priv-app/WhisperplayCore/
    - /system/priv-app/WhisperplayInstall/


- Captive Portal Launcher
    - /system/priv-app/CaptivePortalLauncher/
    - /system/app/CaptivePortalLogin/


- Amazon Voice Support
    - /system/priv-app/com.amazon.vizzini/
	

- Screen Mirroring Function
    - /system/priv-app/WhisperCastConnect/


- Needed For Amazon Settings UI (Removal Will Break Stock Settings)
    - /system/priv-app/DeviceSoftwareOTAContracts/
    - /system/priv-app/RemoteSettingsAndroid/
    - /system/priv-app/RemoteSettingsInternalSDK/
	
- Checks Network Status Under Amazon Settings (has 20+MB RAM footprint)
    - /system/priv-app/SystemStatusMonitor/

<br/><br/>

**TO-DO List**

- Hook a System Shell Script To Run "pm disable" Commands On Boot or First Boot

- Get Google Play Store Working Properly

- Get SuperSU Working Properly After Reboot

- Replace Amazon Settings With Stock Lollipop 5.1 Settings APK

- Remove The Rest of Amazon Bloat (TV Launcher, Amazon Settings, etc)

    * Stock Lollipop or Equivalent Settings APK Required To Remove "com.amazon.tv.*" Packages
	
- Disable Opera Mini Update (Newer Versions Do Not Support FireStick Remote For Mouse Anymore)

<br/><br/>

***Preview of Default Kodi Build***
######\*\* Heavily Modified, Originally Based Off Titanium Build \*\*######

![Kodi Preview 1](https://github.com/esc0rtd3w/firestick-loader/blob/master/misc/preview/kodi/main-menu.jpg)
<br/><br/>

![Kodi Preview 2](https://github.com/esc0rtd3w/firestick-loader/blob/master/misc/preview/kodi/movies.jpg)
<br/><br/>

![Kodi Preview 3](https://github.com/esc0rtd3w/firestick-loader/blob/master/misc/preview/kodi/tv-shows.jpg)
<br/><br/>

![Kodi Preview 4](https://github.com/esc0rtd3w/firestick-loader/blob/master/misc/preview/kodi/live-tv.jpg)
<br/><br/>

![Kodi Preview 5](https://github.com/esc0rtd3w/firestick-loader/blob/master/misc/preview/kodi/sports.jpg)
<br/><br/>

![Kodi Preview 6](https://github.com/esc0rtd3w/firestick-loader/blob/master/misc/preview/kodi/sports-live.jpg)
<br/><br/>

![Kodi Preview 7](https://github.com/esc0rtd3w/firestick-loader/blob/master/misc/preview/kodi/education.jpg)
<br/><br/>

![Kodi Preview 8](https://github.com/esc0rtd3w/firestick-loader/blob/master/misc/preview/kodi/gaming.jpg)
<br/><br/>

![Kodi Preview 9](https://github.com/esc0rtd3w/firestick-loader/blob/master/misc/preview/kodi/documentaries.jpg)
<br/><br/>

![Kodi Preview 10](https://github.com/esc0rtd3w/firestick-loader/blob/master/misc/preview/kodi/mixed-media.jpg)
<br/><br/>

![Kodi Preview 11](https://github.com/esc0rtd3w/firestick-loader/blob/master/misc/preview/kodi/podcasts.jpg)
<br/><br/>

![Kodi Preview 12](https://github.com/esc0rtd3w/firestick-loader/blob/master/misc/preview/kodi/retro.jpg)
<br/><br/>

![Kodi Preview 13](https://github.com/esc0rtd3w/firestick-loader/blob/master/misc/preview/kodi/news.jpg)
<br/><br/>

<br/><br/>

***Preview of Default Kodi Build (Login Screen)***
![Kodi Preview 14](https://github.com/esc0rtd3w/firestick-loader/blob/master/misc/preview/kodi/login-screen.jpg)
<br/><br/>

<br/><br/>

***Preview of Default Kodi Build (Adult Section)***
![Kodi Preview 15](https://github.com/esc0rtd3w/firestick-loader/blob/master/misc/preview/kodi/adult.jpg)
<br/><br/>

<br/><br/>

***Preview of Default Kodi Build (Maintenance Section)***
![Kodi Preview 16](https://github.com/esc0rtd3w/firestick-loader/blob/master/misc/preview/kodi/maintenance.jpg)
<br/><br/>

<br/><br/><br/><br/>

***esc0rtd3w 2016 / firepwn.com***