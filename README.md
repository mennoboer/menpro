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

## 1.2.2 (18-01-2015)

*   Bugfixes for new style (1.2.0)
*   Maximize/Minimize functionality

---

## 1.2.1 (12-01-2015)

*   Themes fully implemented
*   Forms with the console are now resizable

---

## 1.2.0 (18-12-2015)

*	MenPro style overhaul

---

## 1.1.1 (06-12-2015)

*   Added items to Services menu
    *   Start all
    *   Start all (debug)
    *   Stop all

---

## 1.1.0 (04-12-2015)

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

## 1.0.9 (30-11-2015)

*   MenPro-DNS debug format changed
*   Various data validations to prevent exceptions
    *   Vhost: Generate Certificate (SSL settings fields)
*   Added settings for FCGI (Settings -> Apache)
*   Usage of quoted values (with spaces) in the console now works correctly
*   "project" command now looks at Vhosts instead of the directory
*   Added project selection ComboBox to consoles
*   Vhosts: Changed icon for collapse/expand

---

## 1.0.8 (24-11-2015)

*   DNS management
    *   Add DNS zones
    *   Remove DNS zones
    *   Add DNS records
        *   A-record
        *   CName-record
*   Named Pipe to MenPro-DNS
*   Changing DNS records automatically refreshes MenPro-DNS

---

## 1.0.7 (20-11-2015)

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

## 1.0.6 (16-11-2015)

*   Beter vhost management (with folders)
    *   Add folders
    *   Delete folders
    *   Delete vhosts
*   Minor fixes

---

## 1.0.5 (09-11-2015)

*   Vhosts: SSL - full functionality
    *   Generate CA Certificate
    *   Generate SSL Certificates (From CA)
*   Minor fixes

---

## 1.0.4 (02-11-2015)

*   FolderBrowserDialog scrolls to selected location
*   Full vhosts Directory functionality
*   Added dialog elements for vhosts: SSL
*   'exit' command added to console
*   Minor fixes