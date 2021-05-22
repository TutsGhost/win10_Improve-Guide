# The Ultimate Guide for Gamers and Day-to-Day-Users of Win10

---
## INDEX:

### [1. Windows 10](#windows-10)
- Prevent needing to restart your PC on program crashes
- Windows 10 Telemetry, Cortana and More
- Debloat Windows 10 !!Caution advised!!
- Programs you should consider downloading
- Check the system for integrity
- Fixing problems with windows updates
- CPU and memory performance
- Turn off >Mouse Acceleration<
- Stop unneeded background services
- Interface performance boost
- Set File Explorer to open "This PC" as default


### [2. Browser Configuration](#browser-configuration)
- How to set up your Firefox Browser
- How to set up your Brave Browser
- How to set up your Un-Googled Chromium
- uBlock Origin Settings
- Recommended Add-Ons



### [3. Body, Posture and Health](#body-posture-and-health)
- Prevent back pain
- Hand + wrist exercises
- Improve and train your eyesight
- Train focus and strength of your sight
- How to stay calm and make rational decisions
- What food should you eat and how can you really boost yourself for gaming
- Healthier snacks to try while gaming
- Healthy food to gain energy (real performance boost)
- How improve your chair and desk setup


### [4. Mouse](#mouse)
- Grip styles
- What mouse to use
- How to find a sensitivity that sticks for you (FPS Games)
- Practice aiming motions (Aim Lab)



### [5. Keyboard](#keyboard)
- Learn the HOT and TRENDY keyboard terms
- How to safely clean your keyboard
- Useful shortcuts for Windows users

---

## Windows 10

#### Enhancing and debloating your windows should help not only your sanity but also your PCs performance


- Prevent needing to restart your PC on program crashes

  1. press "Ctrl" + "Shift" + "Esc" (your task manager should be open now

		+ Go into "Options" -> click on "Always on top"
   		+ now the Task Manager will always be in the front of any application, no Alt+F4 and pc-restart-fiddeling anymore


- Windows 10 Telemetry, Cortana and More (more privacy oriented)

   [Download the Programm Privatezilla](https://github.com/builtbybel/privatezilla/releases)
   1. This should have a tick: Privacy, Cortana, Remove all built-in Apps except Defaults (if you want a clean windows though just tick Bloatware),
      On "App permissions" tick everything EXCEPT microphone and camera (this ensures that you will be able to use these in certain programs) -> tick: Gaming, Security.
   2. click on "Apply selected" and check with "Analyze" afterwards if the changes have successfully been made (they should show up highlighted in green)


- Debloat Windows 10

	This topic is about a debloating script i forked and worked on as best as i can, i will try to explain exactly what this script will be doing.
  
  You can find the list of programs you can install [HERE](programlist/programlist.md)
  
    This will do the following steps/functions:

    - Removes all Windows Store Apps EXCEPT office, Xbox, and WSL.
    - Removed Telemetry
    - Disables Cortana
    - Deletes various schedules tasks that rebloat the system
    - Remove other bloatware (Candy Crush, Spotify etc.)
    - Set Windows updates to "only security updates" (Don't worry if it says on "updates" that "Some options are managed through your company" are shown on the windows 
      updatepage, this is because the script disables quality updates to only allow security ones) 
    - Fixes problems that other scripts are causing (lock screen and personalization options restricted)

		Now the steps to run the script:
		1. Right Click Windows Menu -> Select PowerShell Prompt (Admin) OR Select Command Prompt (Admin)
		2. Now you can run the command mentioned in step c. which will download and execute the script from my github account.
		3. Type in or paste for no installs: 		
		  `iex(New-Object Net.WebClient).DownloadString('https://git.io/JODRQ')`
		4. Now to make sure it will start to do a restore point, you will see it gives you the option to freely choose what you want it to do.
		5. If you are not satisfied with any of the changes you can allways load the restore point that has been made at the start, see instructions how to do that 			   [HERE](https://www.dummies.com/computers/operating-systems/windows-10/how-to-restore-from-a-restore-point-in-windows-10/)


#### Programs you should consider downloading

> Important to note is: that you don't have, to have them all. Take a look what you think might be usefull, i will mark the ones i deem as important with (+)

- [CPU-Z](https://www.cpuid.com/softwares/cpu-z.html) → this is a program that gathers information on some of the main devices of your system,
   its very handy if you want to look up your Hardware specs (your BIOS can be lied at, CPU-Z is actually good at for example detecting fake hardware)
- (+)[KeepassXC](https://keepassxc.org/download) → must have password manager, don't argue with me, you need it!
- (+)[Notepad++](https://notepad-plus-plus.org/downloads/) or [Sublime Text](https://www.sublimetext.com/3) → both are great text editors!
- (+)[Geek Uninstaller](https://geekuninstaller.com/download) → great tool to COMPLETELY get rid of a program, this tool will even delete the registry entries
- (+)[Firefox](https://www.mozilla.org/en-US/firefox/download/thanks/) or [Brave Browser](https://laptop-updates.brave.com/latest/winx64) → both are great browsers to surf the web on. (stay away from Chrome, Opera and Microsoft Edge!!)
- [Prime95](https://www.mersenne.org/download/) → Prime95 has been a popular choice for stress / torture testing a CPU since its introduction, especially with overclockers and system builders
- [Autoruns](https://docs.microsoft.com/en-us/sysinternals/downloads/autoruns) → manage your executables that launch with windows automatically and more for example the explorer context menu
- [ImageGlass](https://imageglass.org/download) → one of my favourite image viewing tools
- [TeraCopy](https://www.codesector.com/downloads) → copy your files faster and more securely, this tool is great if you work a lot with files
- [LinkShellExtension](https://schinagl.priv.at/nt/hardlinkshellext/linkshellextension.html#contact) → move your game files around without breaking the game
- [Avidemux](https://sourceforge.net/projects/avidemux/files/latest/download?nowrap) → a free video editor to cut, filter, and encode projects (that simple)
- [OpenShot Video Editor](https://www.openshot.org/download/) → it is what it says, a convenient video editor
- [Audacity](https://www.audacityteam.org/download/) → Audacity is an easy-to-use, multi-track audio editor and recorder for Windows, macOS, GNU/Linux and other operating systems
- [OBS Studio](https://obsproject.com/download) or [Streamlabs](https://streamlabs.com/slobs/download) → if you want to record or stream anything on your PC
- [NZXT Cam](https://www.nzxt.com/downloads) → manage your game times and also get a nice looking overlay to look at your CPU and GPU temps etc
- [Mumble](https://www.mumble.info/downloads/) → this is basically teamspeak but with a far better audio quality and more privacy oriented
- [Ninite](https://ninite.com/) → quickly set up your pc by choosing what programms you want to have installed and get them automatically installed with Ninite
- [OCCT](https://www.ocbase.com/) → popular all-in-one stability check & stress test tool
- [Total Commander](https://www.ghisler.com/ddownload.htm) or [Multi Commander](http://multicommander.com/downloads) → a Shareware- Filemanager for Windows; replaces the file explorer from Windows
- [Process Hacker](https://processhacker.sourceforge.io/downloads.php) → A free, powerful, multi-purpose tool that helps you monitor system resources, debug software and detect malware (in short: a more detailed Task Manager)
- [ArchiSteamFarm](https://github.com/JustArchiNET/ArchiSteamFarm/releases) → this tool lets you idle steam games for the trading cards
- [RPCS3](https://rpcs3.net/download) → RPCS3 is a Sony PlayStation 3 emulator and debugger, play PS3 games on your PC
- [Gameranger](https://www.gameranger.com/download/) → play old multiplayer games once again with your friends (most servers are down on old games, this tool fixes this problem)
- [Parsec Gaming](https://builds.parsecgaming.com/package/parsec-windows.exe) → play local games online with your friends


- Check the system for integrity

   - You may want to check your system for integrity issues(especially after updates), run the following in cmd (you can either find it here: "C:\WINDOWS\system32\cmd.exe" or
   if you type in "cmd" in the search bar on windows):
		- sfc /scannow
		- dism /Online /Cleanup-Image /AnalyzeComponentStore /StartComponentCleanup /ResetBase
		- dism /Online /Cleanup-Image /ScanHealth
		- dism /Online /Cleanup-Image /RestoreHealth
!!Be careful this could remove AntiCheat programms running in the image enviroment, this should be safe for most installs though!!


- Fixing problems with windows updates

If you have problems with windows update it can cause quite a hassle

- You can download a diagnostic tool [here](https://support.microsoft.com/en-us/help/10164/fix-windows-update-errors)
- Let it run and see if it fixes any windows update problems


- CPU and Memory Performance

   [Download QuickCpu for this Topic](https://coderbag.com/product/quickcpu)
   1. Check for the CPU Performance Info
   2. Look for the "Enabled cores" and "Parked cores", your "Enabled cores" should show the same amount as "Logical processors" while it should show 0 for "Parked cores"
   3. All index tabs at the bottom should be set to 100% after you have done that hit 'Apply'


- Turn off >Mouse Acceleration<

  1. Press your "Windows-Key"
  2. Go into settings and search for mouse and click on "mouse settings"
  3. There will be something called "Additional mouse options" on the right hand side, click on it.
  4. Then you go to the Tab "Pointer Options" and take off the tick for "Enhanced pointer precision"

- Stop unneeded background Services

  1. Press the "Windows-Key" + "R" and type in "msconfig"
  2. Go to "Services" and tick the box that says "exclude all Microsoft services"
  3. Now look for any services that you don't need and untick them (remember to not disable any Anti-Cheat or AntiVirus Services)


## Browser Configuration


### How to set up your Firefox Browser

   1. Download "profile.zip" from either the discord server or DM me
   2. Press "Windows Key" + "R" on the keyboard. A Run dialog will open
   3. In the Run dialog box, type in:firefox.exe -P (You can use -P, -p or -ProfileManager (any of them should work))
   4. Click OK. The Firefox Profile Manager window should be open now.
   5. Click on "create Profile" name the profile 'Main' and then "start Firefox"
   6. Now type about:profiles and search for the Main profile, open the Root-folder
   7. Delete everything in that folder and paste all files from profile.zip in there -> you can close the folder
   8. Now go back to your Firefox about:config window and press "F5", search for your profile named Main
   9. Click on "Set as default profile" and restart your Firefox
		1. On the right hand side click on the menu button -> Options -> Files and Applications (its in General when you scroll down)
		2. Check if its set to "Ask every time where to save the file to" if not select it.
		3. Go to "Home" -> "Homepage and New Tab" change it to User defined address
		4. Paste this in: https://duckduckgo.com/
		5. Go to "Search" and change the Default Search-engine to DuckDuckGo instead of Google!!
		6. Scroll down and remove every search engine except DuckDuckGo and Startpage
		7. Click the menu icon on the top right -> "Add-Ons" -> click on the cogwheel symbol -> "Check for Updates"
		8. Follow the "uBlock Origin Settings" topic in this guide
   10. Your Firefox is now ready to go!


### How to set up your Brave Browser

1. First of all DO NOT skip the welcome tour!!
2. You don't have to import bookmarks and settings, if you have freshly installed Firefox Browser with this Guide you can import from Mozilla Firefox otherwise just move on!
3. On "Set default search engine" you can decide between "DuckDuckGo" or "Qwant"
4. DONT enable "Brave Rewards" !!
5. Go to the Menu (top right corner) -> "Settings" -> "On Startup" topic select "Open a specific page or set of pages" -> "Add a new page"
6. Depending on what search engine you chose at the tour type in "DuckDuckGo.com" for DuckDuckGo or "Qwant.com" for Qwant
7. "Appearance" -> you want this checked: "Hide Brave Rewards button", "Show home button" 
 (Enter custom address: "DuckDuckGo.com" for DuckDuckGo or "Qwant.com" for Qwant) and "Show bookmarks"
8. "New Tab Page" -> uncheck "Brave Rewards"
9. "Shields" -> "Default View" set it to "Advanced View"
10. "Extensions" -> "Web3 provider for using Dapps" set it to "None"
11. Disable "Hangouts"
12. "Additional settings" -> "Privacy and security" -> check "Send a "Do Not Track" request with your browsing traffic" -> 
   uncheck "Allow sites to check if you have payment methods saved"
13. Your Brave is now ready to go! 	
(Check out "Recommended Add-Ons" in this Guide too! Brave Browser doesn't need uBlock Origin! Also it is not compatible with Mozilla addons but the Chrome Store)


### How to set up your Un-Googled Chromium

1. [Download the latest release here](https://ungoogled-software.github.io/ungoogled-chromium-binaries/releases/)
2. Go to menu in the top right corner -> "Settings" -> "Appearance" -> "Search engine" -> "Search engine used in the address bar" set to "DuckDuckGo"
3. "Advanced" -> "System" -> uncheck "Use hardware acceleration when available"
4. go to chrome://flags/#extension-mime-request-handling in your address bar -> set the highlighted option to "Always prompt for install" -> "Relaunch"
5. Now download the following Add-On:
6. https://clients2.google.com/service/update2/crx?response=redirect&acceptformat=crx2,crx3&prodversion=86.0.4240.183&x=id%3Dcjpalhdlnbpafiamejdnhcphjbkeiagm%26installsource%3Dondemand%26uc
7. https://clients2.google.com/service/update2/crx?response=redirect&acceptformat=crx2,crx3&prodversion=86.0.4240.183&x=id%3Dgcbommkclmclpchllfjekcdonpmejbdp%26installsource%3Dondemand%26uc
8. https://clients2.google.com/service/update2/crx?response=redirect&acceptformat=crx2,crx3&prodversion=86.0.4240.183&x=id%3Dlckanjgmijmafbedllaakclkaicjfmnk%26installsource%3Dondemand%26uc
9. https://clients2.google.com/service/update2/crx?response=redirect&acceptformat=crx2,crx3&prodversion=86.0.4240.183&x=id%3Djchobbjgibcahbheicfocecmhocglkco%26installsource%3Dondemand%26uc
10. https://clients2.google.com/service/update2/crx?response=redirect&acceptformat=crx2,crx3&prodversion=86.0.4240.183&x=id%3Dpkehgijcmpdhfbdbbnkijodmdjhbjlgp%26installsource%3Dondemand%26uc
11. [Chromium Web Store](https://github.com/NeverDecaf/chromium-web-store/releases/download/v1.1.1/Chromium.Web.Store.crx)
12. Now on the right corner there should be a puzzle icon, click it -> click on the icon ![Icon](images/chromestore_icon.png) and update every extension
13. Follow the "uBlock Origin Settings" topic in this guide.
14. Your Un-Googled Chromium is now ready to go!


#### uBlock Origin Settings

This will explain how to set up your Extension to the best settings without breaking any site (meaning functions not working or logins failing)

1. On the top right side of the browser should be a red shield icon ![Icon](images/ubosymbole.png), click on that -> click on this ![icon](images/UblockOverview.jpg)
- Checkmark all the options "Prevent WebRTC from leaking local IP addresses" and "Block CSP reports" on the "Privacy" column
2. Click on "Filter lists" in the upper corner -> click on "[Number] network filters ＋ [Number] cosmetic filters from:" ![Topic](images/Filter%20Header.png)
- Checkmark everything as follows [Link](images/uBlock%20Filter1.png) and [Link](images/uBlock%20Filter2.png)
- "Apply changes" -> "Update now"
3. Follow to this [link](https://jspenguin2017.github.io/uBlockProtector/#extra-installation-steps-for-ublock-origin) and follow the "Extra installation steps 		    	    for uBlock Origin" instructions, to "Subscribe" simply click on the Hyperlink and press OK on the Popup Window.


### Recommended Add-Ons (mainly focused for Firefox (the Mozilla addons page))

Less is better, the ones with a (+) are the ones i deem as important. Don't use any antivirus or vpn addons not only are they not very effective as you might think, they are also very big privacy concerns!!

- (+)Ublock Origin: It is not just an "ad blocker", it's a wide-spectrum content blocker
- Privacy Badger: Intelligent blocker for tracking, this addon learns from your browsing behaviour and gets stronger the longer you use it
- (+)HTTPS Everywhere: An extension to protect your communications by enabling HTTPS encryption automatically on sites that are known to support it (Obsolete in Firefox)
- NeatURL: Clears unneeded parameters from urls to keep them understandable and short
- (+)ClearURLS: Gets rid of unneeded parameters including ones that track you
- (+)LocalCDN: Protects you against tracking through content delivery services
- CSS Exfil Protection:							Protection against the CSS Exfil Exploit used to track you
- Smart Referer:									   	Improve your privacy by limiting Referrer information leaks
- Canvas Blocker:									  Blocks you against Canvas-Fingerprinting
- xBrowserSync:										  Sync up your browser securely even across devices
- Chameleon:										    	A User-Agent-Switcher packed with a lot of privacy enhancing features
- User-Agent Switcher and Manager:		Spoof the "User Agent Header" that gets send
- Terms of Service; Didn't Read:		Shows you how "friendly" the Terms of Service of a website are through a grading system
- Bloody Vikings!:									  Make spam email addresses on the fly
- Dark Reader:										    No longer get blinded by white websites
- Disconnect:										    Visualize and block the otherwise invisible websites that track your search and browsing history (the same as uBlock Origin or Privacy Badger)
- KeePassXC-Browser:									Add-On for your KeepassXC, no longer tedious logins on websites
- Bitwarden:											    Passwordmanager for your browser
- Image Search Options:							Right-click on an image and you will get an option between differOnsOnsent search engines where you can check if it has been uploaded somewhere else
- JavaScript Switcher:								Turn off JavaScript on sites, this can enhance your privacy but will also break some sites

### Interface performance boost

This will help you a bit with your pc performance if you have older hardware mostly this is no longer a huge difference

   1. Open "Windows Search" (right click the windows menu -> "Search")
   2. Type in "Performance" -> click the first result
   3. Now in visual effects you can turn it to "Adjust for best performance"
   4. click "Apply"


- Set File Explorer to open "This PC" as default

This will remove the "recently opened files" section when you open the file explorer

   1. Press "Windows key" + "I" -> search for "file options" -> click on "File Explorer Options"
   2. Change "Open File Explorer to" to "This PC"
   3. At the bottom in the "Privacy" topic untick "Show frequently used folders in quick access
   4. Click "Apply"



## Body, Posture and Health

Fight against soreness, pain and bad posture. Work on your Health/Body. Trust me this is important and can also drastically improve your performance!


- Prevent Back Pain
[Instruction Video](https://www.youtube.com/watch?v=aexDRDS4QqA)


- Hand + Wrist Exercises
[Instruction Video](https://www.youtube.com/watch?v=EiRC80FJbHU)


- Improve and train your eyesight
[Instruction Video](https://www.youtube.com/watch?v=QQ3ki1dCcnw)

[Instruction Video](https://schulte-table.com/)


- Train focus and strength of your sight

[Instruction Video](https://www.youtube.com/watch?v=uJ9fyOkJFfc)
   1. Put the video on fullscreen
   2. Try to focus on the black crosshair/cross in the middle
   3. If you see a green dot moving in a circle around it you are doing everything correctly otherwise try around, you need to fully focus on the center.


- How to stay calm and make rational decisions
[Instruction Video](https://youtu.be/5ddI9KWHZ6U?t=19)

   > Also you can press down on your inner palm of your hand, in the center of it, with the thumb of your other hand, this is a calming technique that might work for you.
[Example Video](https://www.youtube.com/watch?v=FJ77DYyfI0w)


- What food should you eat and how can you really boost yourself for gaming (no its not sugar or energy drinks)
[Video Guide](https://www.youtube.com/watch?v=C0fC7cLQJEg)

   > Don't be scared of fat in food and TLDW; eating avocado, sunflower oil, eggs, chocolate or fish is important and good
[Video talking about the topic](https://www.youtube.com/watch?v=j87OxqFkwaU)


- Healthier Snacks to try

   - Ditch: Potato chips / Try: Toasted pita bread and hummus or veggies with different dips
   - Ditch: Cookies / Try: Mixed nuts with dried fruit
   - Ditch: Sour Patch Kids Candy / Try: Frozen grapes or oatmeal (look for ones with as less sugar as possible)
   - Ditch: Nachos / Try: String cheese and beef jerky
   - Ditch: Hot Pockets / Try: Hard boiled eggs


- Healthy food to gain energy (real performance boost)

   - Bananas
   - Fatty fish
   - Brown rice
   - Sweet potatoes
   - Coffee (It's not recommended to consume over 400mg of caffeine or about 4 cups of coffee per day!!!)
   - Eggs
   - Apples


- How to setup and improve your chair and desk
[Instruction Video](https://www.youtube.com/watch?v=UW_z6bCy1ZI)
Also be sure to get a footrest; not only is it really comfy, but it's also not in the way if you buy a tiny hammock for your feet as a solution ;)



## Mouse

Finding the right mouse and actually improving your movement will do wonders for you, also trying to prevent strain is very, very important!


- Grip styles:

    ![Grip Styles+Explanation](https://image.slidesharecdn.com/gamingmouse-160116084647/95/all-you-need-to-know-about-your-gaming-mouse-5-638.jpg?cb=1452934052)


- What mouse to use:
[Explaining what you can do to find the best mouse for your needs](https://www.youtube.com/watch?v=QVI3mepUHuE)


- How to find a sensitivity that will work for you (FPS Games)
[Video Guide](https://www.youtube.com/watch?v=FLHEn2U7CVw)


- Practice Aiming Motions (Aim Lab):
[Video Guide](https://www.youtube.com/watch?v=nYcPR2aNeRM)


- How to change out your mouse cable
This Tutorial shows you how to safely change your rubber cable to a paracord one. 
Here is why this is good: paracord cables are more durable meaning it will hold waaaay longer than those rubber cables
[Video Guide](https://www.youtube.com/watch?v=HlxCfYajXLU)

   > https://paracablemods.co.uk/ this is where you can get the corded cables (paracords)



## Keyboard

There is not a lot to talk about when it comes to the keyboard, sadly all that makes a difference in choosing a keyboard right now is what type of mechanical keycaps you want to use.
Since I think there is nothing other then opinion based videos out there you should try finding the perfect keyboard for yourself.


- Learn the HOT and TRENDY keyboard terms
https://www.howtogeek.com/310370/all-those-confusing-mechanical-keyboard-terms-explained/


- How to safely clean your keyboard
[Video Guide](https://www.youtube.com/watch?v=_M42Ri3dqoc)

   > cleaning kit, this is not a recommendation but more like a orientation for yourself, please refer to the video :)
   [Amazon Link: Hagibis Multitool Keyboard Cleaner](https://www.amazon.com/dp/B07WRJRXR3/135-6928239-6153718?language=en_US)


- Useful Shortcuts for Windows Users

   - "Shift" and "click" on an application on the taskbar will either = open it or quickly open another instance of it
   - "Ctrl" + "Shift" + "click" a taskbar button = opens an application as an administrator
   - File Explorer Shortcuts:
		- "Ctrl" + "N" = opens a new window
		- "Ctrl" + "W" = closes the active window
   - "Windows key" + "D" = displays and hide the desktop
   - "Windows key" + "E" = opens the File Explorer
   - "Windows key" + "I" = opens Windows Settings
   - "Windows key" + "comma ',' " = lets you temporarily peek at the desktop
   - "Windows key" + "Shift" + "S" = this will take a screenshot of part of  your screen (you can freely select what is being screenshot-ed)
		> to send the screenshot simply press "Ctrl" + "V" in the chat- or text box if you want to save it open any image editor and press "Ctrl" + "V", now you can save the project/screenshot
