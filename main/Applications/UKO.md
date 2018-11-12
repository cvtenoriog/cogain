

# UKO - II

##  Information about UKO-II eye communication system 

NOTE: UKO-II is not supported at the moment, however, you are free to download it on your own risk. 

UKO-II is a communication system that adapts to the needs of the user by providing customizable keyboard layouts and varying number of buttons. UKO-II is based on an open architecture for a communication system, with publicly available sources of the programmable and extendable Emacs text editor, which already includes many text entry and manipulation functions. Furthermore, the operating system support (e.g. sockets), basic applications like mail, and a development environment with extensive documentation are at the programmer's fingertips. All components in the communication aid dealing with input/output have been implemented as Emacs Lisp modules. 

The system is customizable to differing keyboard layouts and to the selection of word suggestions or additional editing commands. 

UKO-II is designed by Karin Harbusch and Michael Kühn in the [University of Koblenz-Landau][3]. Unfortunately UKO-II is not supported at the moment. You can read more about how it functions in a paper found here: [PDF][4]

|![][1]<br>UKO-II<br>|
|---|




##  About UKO-II 

**In order to run UKO-II, you have to do the following:**  

1. Have a running XEmacs (you can get one at ). 
2. Unpack the sources. 
3. Start XEmacs, go to the menu item "Options" > "Edit Init File" 
4. Insert following lines:  

    
    
        (set-frame-size (selected-frame) 85 30)        ;; to avoid bug with too
    small buttons
        (set-frame-position (selected-frame) 0 0)
    
    
            (setq uko-emacs-directory "C:\ whatever path to \UKO-II\") ;;
    take care of the double backslashes!
            (load-file (concat uko-emacs-directory "lisp\uko-ii.el"))
            (uko-init)
        (uko-set-english)
    

1. Save the file with menu item "File" > "Save init.el". 
2. Re-run XEmacs. It should load and initialize UKO-II. 
3. Enter keypresses with mouse or NUM keypad 1,2,3,0. 
4. After typing the word, press "Word / Text" and either  
a) "Select" for taking the highlighted word in the text buffer, or  
b) "Hit List" for switching to the word list on the right side. Choose with "Previous" and "Next".  
Finish with "Select". 
5. If something goes wrong at any time using UKO-II - I'm sure it will:  
1\. Make sure the cursor is inside the text buffer.  
2\. Go to menu item "View" > "Un-Split (Keep This)".  
3\. Press "Alt-X".  
4\. Restart UKO-II by entering without quotes "uko-init" and .  

**Note** UKO-II development is suspended at the moment and we cannot provide support for it at the moment. However, you are free to download it on your own risk. If you have any comments, please send them to [harbusch@uni-koblenz.de][5]. 

##  Download UKO-II 

Please read the information [About UKO-II][6] carefully before you download UKO-II. 

Please tell us more about you before you download UKO-II: 

Your name: (Required) 

Email address: (Required) 

Country: 

First language: 

Do you have a disability relevant to gaze interaction? 

Age: 

Where did you hear about COGAIN? 

Would you like to receive news on services and updates of the system by e-mail? 

May we contact you by mail in case we would like to know your opinion about our systems? 

  
**Download the file here: [File:UKO-II-dl-package.tgz][7]**

[1]: http://wiki.cogain.org/images/thumb/5/57/UKO-II.jpg/180px-UKO-II.jpg
[2]: http://wiki.cogain.org/skins/common/images/magnify-clip.png
[3]: http://www.uni-koblenz-landau.de/
[4]: http://www.uni-koblenz.de/~harbusch/harbusch-kuehn-eacl2003.pdf
[5]: mailto:harbusch%40uni-koblenz.de
[6]: http://wiki.cogain.org#About_UKO-II
[7]: http://wiki.cogain.org/index.php/File%3AUKO-II-dl-package.tgz "File:UKO-II-dl-package.tgz"

  
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTI0MTMzMDM0Ml19
-->