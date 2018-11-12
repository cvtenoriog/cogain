# Gazetalk About

  
About GAZETALK 5.2.2, Released Nov. 2006 

Please read this carefully before you download Gazetalk 

GazeTalk has been designed and developed by **The Eye Gaze Interaction Group at The IT University of Copenhagen ** [http://www.itu.dk/research/EyeGazeInteraction/](http://www.itu.dk/research/EyeGazeInteraction/) in cooperation with the **IT-Lab at The Royal School of Library and Information Science, Copenhagen**

**PEOPLE INVOLVED:**  
Design and testing by John Paulin Hansen, Anders Sewerin Johansen, Haakon Lund, Henning Dahl, Kristian Tørning, Birger Bergmann Jeppesen, Arne Lykke Larsen, Christoffer Soya, Dan Witzner Hansen, Kenji Itoh, Hirotaka Aoki, Andrew Junker, Leonard G. Robbins, Paivi Majaranta and Inge Wilms.  
Language processing by Anders Sewerin Johansen.   
System development and programming by Anders Sewerin Johansen & Yujing Lai.   
Original UI components donated by SecondGuess ApS ([www.secondguess.dk][1])  
Thanks to Ole Brunbjerg for advices.  
Thanks to The Danish Association for Neuromuscular Diseases for cooperation.  
German version of Gazetalk edited and translated by Michael Heubner, Psychology Dept., Dresden University of Technology. 

**FUNDING:**  
Ministry of Science, Technology and Innovation, Denmark  
COGAIN Network of Excellence, IST EU 6. Research programme ([[[1]][2]])  
The Nordic Academy for Advanced Study (NorFA)  
Grant-in-Aid for Scientific Research, Japan Society for the Promotion of Science  
Bilateral Program for Scientist Exchanges under Memoranda of Understandings between JSPS and Danish Rectors' Conference 

###  CONDITIONS OF USE: 

Disabled people can use the system as it is. The systems may also be used for research purposes. Permission to use the system for ANY OTHER PURPOSES, should be obtained from The Eye Gaze Interaction Group. Interface elements are patent protected (US pat. 005625380A). The Eye Gaze Group will not be responsible for any possible damages caused by the GazeTalk system. Unfortunately, we do not have resources to assist with any technical problems that may occur. We appreciate if you send comments to [**gazetalk@itu.dk][3]**. 

November 2006  

[Download Gazetalk][]

Hansen, J.P., Lund, H., Aoki, H. and Itoh, K. (2006) Gaze communication systems for people with ALS, ALS Workshop (in conjunction with ALS/MND 2006), Yokohama, Japan [[[File:ALS_Workshop_Yokohama2006.pdf PDF ]]]   
The presentation given at the workshop can be seen [**here ][5]**

###  NOTICE: 

GazeTalk does not include any gaze- or head tracking facilities. It may be operated by mouse, joystick, or any other input method that is capable of controlling the pointer function. The design is specifically meant to support head or eye control. 

###  INSTALLATION: 

When you install GazeTalk the installer ask for installation drive and directory. Usually GazeTalk suggest C:Program FilesGazeTalkGazeTalk5. The main application file is "GazeTalk5.exe" found in that directory; double clicking it starts the GazeTalk5 application. (Config.exe starts the configuration setup for email etc, see below for more information and instructions.)   
If you have problems with installation, please read the notes at [GazeTalk Wikit page][6]

###  MUSIC, VIDEO, PDF, TEXT and MAIL-FILES: 

To get access to PDF-files, Multimedia-files (video and music) and text-files from within GazeTalk you have to copy the files to the following directories which are all found in the installation directory of GazeTalk:  
PDF - files should go into PDF;  
Music - files into MUSIC;   
Video - files into MOVIE and   
Text - files into text  
If you choose to use the mail - function in GazeTalk received and sent mails are stored in the directory mail. 

If you install a new version of GazeTalk please remember to backup your data and e-mails before doing so. The data and e-mails can then be copied back into the above mentioned directories after finishing the installation / upgrade 

###  HOW TO RUN THE SYSTEM: 

GazeTalk is available in English, Italian, Japanese and Danish. Each language is provided as an installation package. You install GazeTalk by activating the downloaded msi-file. If you want to install further languages, you can do so by downloading the relevant language pack and activate the installer. The system may be downloaded from [Gazetalk#Download_Gazetalk][4]. 

Before running GazeTalk you can run the config.exe program to configure you e-mail account, to set system preferences and default layout. To run Gazetalk, double click GazeTalk5.exe (found in the same directory as config.exe, typically C:Program FilesGazeTalkGazeTalk5). 

_Most of the system preferences and layout settings can be changed by the user from within the GazeTalk program. GazeTalk will remember the new settings when leaving the program. _

###  E-MAIL: 

**E-mail account settings** are only needed in case the user actually intents to use GazeTalk for sending and receiving e-mails. The settings are done in the fields shown in figure 1

|![GazeTalk email settings dialog][7] <br>Figure 1: Configuration of e-mail in GazeTalk<br>|
|:---:|
 

You should see the instructions from the user's internet access provider for the details that has to be entered into the mail settings. Remember to check "Use modem" if you are using a dial-up connection. Dial-up connections will appear in the list below the checkbox. 

###  PREFERENCES: 

|![GazeTalk preferences dialog][8]<br>Figure 2: Preferences<br>|  
|:---:| 

**Remember my words:** When selected, GazeTalk will remember all words typed by the user and will give high priority to these words in the word predicted. We recommend that this is selected WHEN the user has become familiar with GazeTalk, since all spelling mistakes will also be remembered. 

**Click mode** works by a normal mouse click-function. We recommend click-activation used in combination with any pointing device, if the user has sufficient control to perform a click. Click activation can be achieved with any kind of switch. We have successfully used the Brainfinger EMG switches from CYBERLINK together with GazeTalk. Notice that clicks will also work in combination with dwell mode (see below). 

**Dwell mode** makes selections by dwell time activation. The dwell time should be adjusted by the user from within GazeTalk. Most users find it comfortable to have a dwell time of 1000 ms for a start, but some users prefer a longer dwell time. Very experienced users may be able to handle a dwell time as short as 300 ms. Some users prefer to use a switch in combination with dwell time: They have the dwell time set at 1200 ms or more, but make most selections by their switch before the 1200 ms has elapsed. 

Please note that some gaze tracking systems, have their own dwell time setting and a global dwell time function. This may interfere with the dwell time function in GazeTalk. You can then either chose to have a longer dwell time setting in GazeTalk than in the gaze tracking system, or to use GazeTalk in click mode. We recommend that some different combinations settings are tested with the user. 

**Auto scan mode** will make GazeTalk automatically jump from button to button and can be use in combination with any kind of switches that will produce a click function. The scan time can be adjusted from the setup menu ("scan interval"). During step-scan, there will be a short brake after each click activation. The length of the click-pause can be adjusted in the setup menu also ("In scan mode, pause time"). It can have an impact on typing speed to find the right pause time for a particular user, so we advice spending some effort on fine-tuning the pause time. 

The steps scan function may be stopped anytime by pressing Esc, but GazeTalk should be the active window for this to work. 

The user can reverse the scanning direction by activating the shift key or F12. This makes it possible for the user who has control of more than one switch to change directions on a second switch. The second switch should then be set to produce a key-code for "Shift" or "F12". Please see the manual for the specific switch in use for how to do this. 

**If no input change to scan:** GazeTalk will automatically reverse to the auto scan function if the mouse has not been activated for a specific time that can be set by the "Change to scan after (sec)" - slider. This feature is included in GazeTalk to provide a backup for pointer interaction by gaze, which is known to sometimes loose connection with the users eye. The function should only be activated if the tracker actually fails often and if the user has a switch available. 

**Voice** functions are activated via the SAPI interface. Choose the SAPI interface for the particular version of Windows (98, 2000, XP) in use. If you install third-party SAPI compliant voice, please follow the instruction as indicated by the manufacture. The clipboard option is to be used for local version of non-SAPI proprietary voice systems. It may be decided when to read loud the written text, either after each word, sentence, paragraph or never. 

Ask for log file name at start up: This function is only to be used for research purposes. When activated, the user will be asked to indicate a name for a log file that will contain every single action taken during the following session. Researchers should try this facility and may contact us to get more information on data interpretations and the data summaries provided (contact [gazetalk@itu.dk][3]). 

###  LAYOUT: 

|![GazeTalk layout control settings][9]<br>  Figure 3: Layout control settings <br>|
|:---:|

**Character Preview:** This function should only be used in combination with dwell time. During dwell time the user will get information on the location of the next six characters once the present character has been activated. This helps preparing for the next move and reduces search time. Some users find it distracting to have the character preview turned on, especially when they are unfamiliar with GazeTalk. 

**Character distribution:** "Fixed character position" will only provide a simple (so called 1-gram) prediction of the next 6 characters. These locations are easy to learn and therefore we recommend that "Fixed character position" be used during the first 10 hours of typing. By changing to a "Dynamic character position" the predictor will become more sensitive (using so called 3-gram predictions) and this will increase typing speed. Characters will still be located at the same position as in the "Fixed character position" most of the time, but sometimes they may be pushed away from their primary position to another position, if another character that share the same character position has a higher probability. A skilled user will be able to detect these occasional changes during the dwell period, if the pre-view function has been activated. 

**Text field background colour:** If the user has problems with the high contrast between the white text field and the black buttons, it is possible to change the text field background to black. **Note on the colour coding of labels and characters:** The colour scheme of GazeTalk consists of black background and white, green or yellow characters in order to obtain maximum contrast. White characters indicate that a final execution will take place. A yellow colour indicates that more functions will become available. A green colour indicates that this function will bring you one level up in the hierarchy. 

**Accumulate dwell time:** In a normal dwell time setting GazeTalk will re-set the dwell time counter whenever the user leaves a button. However, if the user has very big difficulties fixating a button, and if the pointer are often jumping to another button, then the accumulate dwell time option may be used to avoid the re-setting of a button. This can also be an effective way to make gaze interaction possible with in-accurate, low-resolution gaze trackers or if the user is only able to obtain a poor calibration. Please note that activating the "Accumulate dwell time function" will not make any difference to the visual display of the buttons. 

**Number of words suggested:** The system gives one-word suggestions as default. This is 15% more effective for novice users than 4 or 8-word suggestions. Some experienced users, who have used the system for longer time, prefer to have 2 to 8 word suggested. However, we only recommend this change when the adaptive word prediction has been used for several weeks. We do not recommend using the adaptive word prediction if the user misspell words often. Please note that a high number of word suggested (e.g. more than 4) will make the font become smaller on the word button. Since users also will look at the word in the button of the list of suggested words this may cause the button below the word button to become selected if the tracking systems is not very accurate. 

**GazeTalk window size:** This will be the size of the GazeTalk window when launched. The user may change window size from within the application and the new setting will then be remembered. 

**Editor text size:** This will set the default size of typed text in the text field. 

**Minimum font size of button:** This will set the size of characters shown in buttons. However, if there is more than 4 words shown, or if the window size is very small, the font size can become smaller than the minimum setting. 

###  PATH: 

|![GazeTalk paths settings][10]  <br> Figure 4: Location of Dasher and specification of the default layout <br>|
|:---:|

**Location of Dasher:** GazeTalk 5.2.2 provides direct access to the very fast Dasher typing system. This system can be downloaded from  in several different language versions. Once Dasher has been downloaded and installed, you should indicate where it is located on the computer (Choose Dasher location). Access to Dasher from within GazeTalk has been put on the very front layout of GazeTalk to remind the user that he or she could try it, every time GazeTalk is turned on (Figure 5). 

|![GazeTalk provides direct access to Dasher][11]  <br> Figure 5: The frontpage layout of GazeTalk provides direct access to Dasher.<br> |  
|:--:|


Once the Dasher button gets activated the user will se a divided layout in which the Dasher systems takes up a window to the left and the standard GazeTalk layout to the right. The user can start input to Dasher, control the typing speed of Dasher (faster/slower) and export the text written in Dasher directly to GazeTalk ("Text to GazeTalk"). In GazeTalk the user is then able to continue writing and/or editing, and use the text for e-mails, documents or just as type-to-talk. Text that are written in Dasher and exported to GazeTalk will be included in the database of user words. The words will therefore be predicted with a high likelihood in all future text production within GazeTalk. 

**Choose layout:** This field, shown in figure 4, is used to indicate the location of the layout (language version) that GazeTalk should load on start-up. You change between the installed languages from within GazeTalk. You will find the change language function in the SETUP - menu. Please have patience since it may take more than a minute for the changes to become effective. GazeTalk will remember the layout in use when the system was exited last. 

###  KNOWN ISSUES: 

The web browser of GazeTalk is not particular stable. In fact, some web pages with Javascript may crash GazeTalk. Should this happen, GazeTalk may have to be re-started. We are sorry for this and working hard to solve the problem. Meanwhile, we recommend that the user only visit new web sites when there is someone besides him to help should GazeTalk crash. 

###  SYSTEM REQUIREMENTS: 

PC with mouse (or joystick, head- or eye- tracking)  
Windows 2000 or newer 

A synthetic voice installed (SAPI 4 or SAPI 5). English synthetic voices can be downloaded free of charge at:

SAPI5: (Windows 2000)  


SAPI4: (Windows 2000)  


Adobe Acrobat Reader 7.0. or newer **IMPORTANT**: There is an automatic update function in Adobe Acrobat. The automatic update is not compatible with GazeTalk and it will subsequently hold GazeTalk. To avoid this you can either disable the automatic update or you can choose to update Adobe Acrobat and restart GazeTalk. 

Microsoft Multimedia Player 9.0. In GazeTalk the playback of mp3 music files, mpg and wmf video files are supported. 

External, adjustable speakers are recommended.  

([PDF version of this manual][12] is included in the GazeTalk installation packet.) 

[Short manual on data recording in GazeTalk ][13]

[Download Gazetalk][4]

[1]: http://www.secondguess.dk
[2]: http://www.cogain.org
[3]: mailto:gazetalk%40itu.dk
[4]: /main/Applications/GazeTalk.md
[5]: http://www.cacr.media.teu.ac.jp/grant/als/video/5.asx
[6]: http://itlab.dbit.dk/wikit/index.php/GazeTalk#Installation_errors_etc
[7]: /Img/GazeTalk5-configuration-email.jpg
[8]: /Img/GazeTalk5-configuration-preferences.jpg
[9]: /Img/GazeTalk5-configuration-layout.jpg
[10]: /Img/GazeTalk5-configuration-path.jpg
[11]: /Img/Gazetalk5-frontpage.jpg
[12]: /Doc/Short_manual_for_GazeTalk_5_2_2.pdf 
[13]: /Doc/Data-recording-in-gazetalk.pdf

  
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTIwOTc4MjQwNjksLTIwNTE4NTg2MTldfQ
==
-->