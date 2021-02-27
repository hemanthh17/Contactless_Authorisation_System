# Contactless_Authorisation_System
## Description
We identified the need to go contact-less especially while checking-in as well as out during office hours in corporate houses as well as govt. institutions. It's an alarming need post lockdown knowing the harsh consequences this pandemic had brought-in. Thus, to inculcate this very need of being contact-less in our new-normal daily routine, we thought to take the aid of trending tech-blend and come out with an implementable solution to kill the raised concern.
Our basic idea is to keep a tight check on the entry module of any office and this we are going to perform via matching the unique IDs of the entering employees with the authorized entries(already saved in the concerned company's database). If it matches, the person would be considered an authorized one to claim for entering within, otherwise not.
For displaying this, we are employing three basic(yet useful) platforms, namely, TINKERCAD, SQLlite,ThingSpeak
The authorized entries are already acknowledged by the database we would have, we have coded some significant python functions via importing relevant libraries in order to settle down the issue of authorization check. Combining both the code-modules, SQLlite as well as authorization-check (written in python lang.), we would pass on the available claimers(unique IDs of the employees to check-in) to thingSpeak(), which would certainly segregate the authorized as well as un-authorized IDs (i.e., into two field planes) based on the code-module constraint and finally, would pass on the info to TINKERCAD(it will read the written info on thingSpeak())
Based on the circuit we have designed, a servo-motor would be enabled for the authorized ones indicating that the door is opening for them to enter and vice-versa.

## Tech Stack
We have used the following
1) ThingSpeak API
2) TinkerCAD Circuit Design
3) Jupyter Notebook
4) SQL

## Libraries and dependencies
The libraries that will be required are
1) sqlite3
2) Numpy
3) Pyzbar
4) OpenCV
5) urllib
6) requests

## Installation steps
There will be requirement of a software which can accomodate .ipynb files and along with that usage of TinkerCAD to visualise the Circuit working
### Jupyter Notebook
1) Install Anaconda Navigator and our systems had 64-bit Windows-10 OS
2) Post installation procedure open the Anaconda Navigator and click Jupyter Notebook
3) Now a file tree is opened and navigate to the file system where you had downloaded the above file and click it
4) Now the notebook opens and wach cell can be executed 
### Google Colab
1) Open any Web Browser and navigate to https://colab.research.google.com/notebooks/intro.ipynb#recent=true 
2) Open a new notebook and click file 
3) Click upload notebook and navigate to the file system where it was downloaded.
4) Now you can execute cell by cell and observe the output

### ThingSpeak 
1) Navigate to https://www.thingspeak.com
2) Create an account or login
3) Navigate to Channels and click public channels
4) Based on the user ID you can monitor the intermediate output received
5) In specified channel which is made public the values from the notebook can be seen on the graph

### TinkerCAD
1) Navigate to https://www.tinkercad.com 
2) If you do not have an account then create an account
3) Now a link will be shared with you and you can open the link directly to check the code and begin executing
