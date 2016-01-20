# MenPro
MenPro is a full-featured free webserver-suite. Set-up in a few clicks and easy to use.
The most important feature of MenPro is being able to get a working webserver in a few clicks. No settings to set, and ready as-is.

![MenPro](<http://d.pr/i/1iCsP+>)

The suite contains the following features; 

#### Webserver 
###### Apache
    Versions included;
      - 2.4.17
    
###### PHP
    Easy to switch versions in 1 click
    Versions included;
      - 5.4.45
      - 5.5.30
      - 5.6.14
      - 7.0.0

###### Vhosts management 
    Add new vhosts 
    Set a different PHP version for each vhost (optional) 
    Add servername and serveraliasses to DNS server
    
![Vhost management](<http://d.pr/i/1kfUA+>)
    
###### SSL 
    Generate Root Authority 
    Generate certificates from Root Authority 
    
###### Process Management 
    View all running PHP processes 
    Kill (all) PHP processes
    
#### DNS 
    Add DNS zones
    Add DNS records 
    A-records
    CName-records

![DNS Management](<http://d.pr/i/10bqU+>)

![MenPro-DNS](<http://d.pr/i/162rc+>)
    
#### SMTP & POP3 
    Send e-mail to the SMTP server on port 25 
    Retrieve e-mail through the POP3 server on port 110 

![MenPro-SMTP](<http://d.pr/i/1aLgM+>)

---

# MenPro Changelog

## Future Plans

*   php.ini management
*   More (personal)settings
*   Export/import websites (with settings)
*   Contextmenu for consoles
*   Manage PHP & Apache versions
    *   Download from remote server (install/delete)
*   Seperate php.exe for using PHP in CLI applications
*   Cron functionality
*   Enable/disable Apache modules

---

#### 1.2.4 (22-01-2016)

*   MenPro-DNS will find the longest match when using a wildcard instead of the first match, e.g. *.test.nl will have a lower priority than *.sub.test.nl on matching
*   Bug: MenPro crashes when adding a new vhost

---

#### 1.2.3 (19-01-2016)

*   Icons added for MenPro-DNS and MenPro-SMTP
*   Icons added to main menu
*   Icons added to all forms
*   Status icons added to main menu (Services)
*   Updated README.md
*   Padding in MenProTreeView changed
*   Fixed DNS records being deleted if the checkbox was not checked
*   Search bar cancel icon fixed (had a white background)

---

#### 1.2.2 (18-01-2015)

*   Bugfixes for new style (1.2.0)
*   Maximize/Minimize functionality

---

#### 1.2.1 (12-01-2015)

*   Themes fully implemented
*   Forms with the console are now resizable

---

#### 1.2.0 (18-12-2015)

*	MenPro style overhaul

---

#### 1.1.1 (06-12-2015)

*   Added items to Services menu
    *   Start all
    *   Start all (debug)
    *   Stop all

---

#### 1.1.0 (04-12-2015)

*   SMTP & POP3 server added
    *   Send e-mail through SMTP to localhost
    *   Retrieve e-mail through POP3 from localhost
*   Services menu item added
    *   DNS moved to Services menu item
    *   Apache menu added to Services menu
    *   SMTP menu added to Services menu
*   Vhost management fixes
    *   New Vhost addition to list fixes
    *   Other minor fixes
*   Console changes
    *   Colors added to console
    *   Console speed optimizations
    *   Time added to console
*   Minor fixes

---

#### 1.0.9 (30-11-2015)

*   MenPro-DNS debug format changed
*   Various data validations to prevent exceptions
    *   Vhost: Generate Certificate (SSL settings fields)
*   Added settings for FCGI (Settings -> Apache)
*   Usage of quoted values (with spaces) in the console now works correctly
*   "project" command now looks at Vhosts instead of the directory
*   Added project selection ComboBox to consoles
*   Vhosts: Changed icon for collapse/expand

---

#### 1.0.8 (24-11-2015)

*   DNS management
    *   Add DNS zones
    *   Remove DNS zones
    *   Add DNS records
        *   A-record
        *   CName-record
*   Named Pipe to MenPro-DNS
*   Changing DNS records automatically refreshes MenPro-DNS

---

#### 1.0.7 (20-11-2015)

*   DNS Server
    *   Seperate server (application)
    *   Normal mode
    *   Debug mode
*   Default settings on first startup
*   Remove settings for Apache & PHP location
*   Check for spaces in base directory
    *   FCGI in Apache does not support spaces
*   MenPro exception logging
*   Help file (not complete)
*   Minor fixes

---

#### 1.0.6 (16-11-2015)

*   Beter vhost management (with folders)
    *   Add folders
    *   Delete folders
    *   Delete vhosts
*   Minor fixes

---

#### 1.0.5 (09-11-2015)

*   Vhosts: SSL - full functionality
    *   Generate CA Certificate
    *   Generate SSL Certificates (From CA)
*   Minor fixes

---

#### 1.0.4 (02-11-2015)

*   FolderBrowserDialog scrolls to selected location
*   Full vhosts Directory functionality
*   Added dialog elements for vhosts: SSL
*   'exit' command added to console
*   Minor fixes