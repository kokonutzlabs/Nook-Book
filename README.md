# Nook_Book.HTML

Hello,
Nook_Book is a small, controlled web application created to understand how HTML, PHP, and SQL interact in a basic system environment. While the project is themed around Animal Crossing and visually modeled after a social media profile, its long-term purpose is to serve as a learning platform for digital forensics and data integrity concepts.

Version 1 focuses exclusively on system setup and baseline behavior. No authentication, security controls, or forensic logging are implemented at this stage.

## Purpose
The goal of Version 1 is to:
- establish the application structure
- define how user interaction data is stored
- create a known “normal” state of the system
- document system components before introducing incidents or analysis

This baseline will be used in later versions to compare changes, investigate anomalies, and analyze system behavior.

## System Scope
At this stage, the system supports:
- a static HTML profile page
- basic user interaction via form submissions
- backend processing with PHP
- storage of interaction data in a SQL database
- local execution in a controlled environment (XAMPP)

The system does not include:
- user authentication or sessions
- access controls
- input validation beyond basic handling
- logging or audit trails
- security hardening

These exclusions are intentional and documented.

## File Explainations:
#### HTML
##### **nook-book.html:** Displays a single villager profile. Users can submit interactions such as votes, reactions, or comments through HTML forms.
#### PHP
##### **nook-book.php:** Handles form submissions and displays confirmation messages after user interaction
##### **nook-book-db1.php:** Creates the SQL database used to store interaction records.
##### **nook-book-conn1.php:** Establishes the database connection between the application and SQL backend.
##### **nook-book-setup1.php:** Creates the database tables used to store submitted form data.
##### **nook-book-forms1.php:** Captures user input from HTML forms and inserts the data into the database.
## Programs Used:
- VS Code
- XAMPP
- PhpMyAdmin
## Languages Used:
- HTML
- CSS
- PHP
- SQL

## Data Handling
In Version 1:
- each form submission results in a new database entry
- records are stored without user identification or authentication
- data is not edited or deleted once inserted
- database entries represent raw interaction records

This version establishes a baseline dataset for future comparison and analysis.

## Sources I've Used:
- [w3schools](https://www.w3schools.com/)
- [PHP TUTORIAL](https://www.phptutorial.net/php-tutorial/php-radio-button/)
## How To View The Site
#### Option One:
###### If it's still up, you can view the project through my [Neocities Page](https://fuzzykokonutz.neocities.org/). It is in the project section of the page and is the first link on the list. But you will not be able to use the interactions, since it doesn't allow backend.
#### Option Two:
- 1.Download [XAMPP](https://www.apachefriends.org/download.html) (this gives you a local host to run the php and mysql files)
- 2.Download each file I provided. (if you want the social experience, exclude nook-book.php)
- 3.Create and name a folder to put the downloaded files in. (save it in the local host files)
- 4.After setting up your XAMPP, open it and start the Apache and MySQL.
- 5.Open your browser and enter ex.) localhost/(whatever the folder name is) in the search bar.
- 6.When the local host is open, click on the nook-book.html file. (Viola, enjoy! ⸂⸂⸜(രᴗര๑)⸝⸃⸃ )

## Planned Future Versions
- Version 2: interaction logging and system visibility
- Version 3: simulated incidents and data integrity analysis
- Version 4: forensic investigation and reporting

## Updates 
1. I will add more to the html later on 12/31/25
2. I made a new repository for my next step for my project.
3.  I will fix the php data transfer without interrupting user experience. 1/1/26
