## Current Projects

### willis240.github.io
#### Making a personal webpage 

**In Progress:**
- Updating the website with new things I've done/learned each day

## Summer Internship 2020

### Week 1

#### May 18

- Read the [Github guides](https://guides.github.com/)
- Made this webpage
- Installed Ubuntu 20.04 on WSL

#### May 19

- Read an article on becoming a [Command-Line Ninja](https://towardsdatascience.com/this-will-make-you-a-command-line-ninja-93a51cdb16b1)
- Read up on using [Markdown](https://www.markdownguide.org/basic-syntax/) to make a webpage
- Read up on the [Resource Workspace Data Organization documents](https://researchworkspace.com/help/Overview.html)
- Watched and participated in a Python tutorial

#### May 20

- Researched differences between [backups and archives](https://www.networkworld.com/article/3285652/backup-vs-archive-why-its-important-to-know-the-difference.html)
- Researched differences between [real time, near-real time, and batch](https://blog.syncsort.com/2015/11/big-data/the-difference-between-real-time-near-real-time-and-batch-processing-in-big-data/)
- Went through a [tutorial about the Linux command line](https://ubuntu.com/tutorials/command-line-for-beginners#1-overview)
- Read an article on how [IoT and Grafana are affecting rural Africa](https://grafana.com/blog/2019/05/01/how-iot-and-grafana-are-enabling-electrification-across-rural-africa/)
- Went through a [more in-depth Python tutorial](https://github.com/trekhleb/learn-python)

#### May 21

- Finished going through the more in-depth Python tutorial
- Got a development environment for Python setup in Ubuntu (I previously just had one in Windows)
- Wrote a Google Doc about goals for the summer
- Worked on some [Python katas](https://www.codewars.com/collections/easy-python-katas) to get my skills up

#### May 22

- Completed several Python katas from the same site as yesterday
- Read through a [cheat sheet](https://www.educative.io/blog/bash-shell-command-cheat-sheet) on commands for Linux bash (as well as how to make aliases)

### Week 2

#### May 25

- MEMORIAL DAY

#### May 26

- Constructed the Raspberry Pi box
- Set up the Raspberry Pi
- Created small presentation for introducing me to ACEP
- Created short tutorial on constructing the top half of the Raspberry Pi box

#### May 27

- Read the [documentation](https://shelly.cloud/wp-content/uploads/2019/12/Shelly1PM-UserGuide-EN-web.pdf) on the Shelly Wifi Relay Switch with power metering
- Tried to get pandas (a Python data analysis library) installed in Ubuntu, to no avail
- Read a [tutorial on Jupyter Notebooks](https://www.dataquest.io/blog/jupyter-notebook-tutorial/)
- Installed Anaconda on Windows, but haven't successfully connected it to PyCharm yet

#### May 28

- Successfully connected Anaconda to PyCharm (Windows)
- Went through a large part of this [Python Pandas Tutorial](https://www.learndatasci.com/tutorials/python-pandas-tutorial-complete-introduction-for-beginners/)

#### May 29

- Fixed Ubuntu's "404 Not Found" error when trying to install Telegraf and installed Telegraf
- Installed Influxdb
- Fixed Ubuntu's "404 Not Found" error in general by upgrading from Ubuntu 19.04 to 19.10
- Installed pip and Python3's influxdb library

### Week 3

#### June 1

- Tried out Python3's influxdb library for a bit
- Installed Grafana
- Attempted installing Docker in Ubuntu, but the repo was "not found"
- Worked on making slides explaining the binary magic in converting two 8-bit int registers to a floating point number

#### June 2

- Got a TIG Stack set up and running flawlessly in Ubuntu
- Finished slides explaining the binary magic
- Fixed Raspberry Pi's wifi issues by doing "sudo apt-get upgrade" over ethernet
- Installed Telegraf, Influxdb, and Grafana on Raspberry Pi

#### June 3

- Uninstalled Influxdb and installed a newer version, then set it up
- Uninstalled and reinstalled Grafana, now just having password issues
- Read this [post about how computers manage time](https://dayne.broderson.org/2020/03/12/the_time_is_now.html)
- Fixed password issues so the Raspberry Pi now has a working TIG Stack
- Wrote a python program that can get ping, download, and upload speeds but needs to be rewritten to test ping with Google.com

#### June 4

- Learned about MQTT through Dayne's interactive tutorial
- Downloaded and used Adobe Acrobat to digitally sign document for going to the lab during COVID
- Started this [tutorial on Node-RED](https://projects.raspberrypi.org/en/projects/getting-started-with-node-red/4), but realized I don't have any resistors and can't continue
- Worked on getting ping, download, and upload speeds displayed in Grafana but came across "Network Error: Bad Gateway(502)"

#### June 5

- Read a [guide on MQTT](http://www.steves-internet-guide.com/mqtt/) to learn a bit more about it
- Fixed problems in Grafana, now have a graph displaying two data points successfully
- Made a program that pings Google but does not yet send the data to the database; got some help from [this guide](https://www.influxdata.com/blog/getting-started-python-influxdb/)
- Went to the University and got the weather station from Matt

### Week 4

#### June 8

- Struggled with internet troubles but eventually got it working
- Went through this [tutorial on working with JSON files](https://realpython.com/python-json/)

#### June 9

- Got google ping data to the influx database, though ping's output is a block of text for each ping
- Went to the Lab with Matt and got the Shelly 1pm wired up successfully to an extension cord
- Got ping's output text formatted so that the data put into the database is the average amount of time for the ping
- Started the Jupyter Notebook for explaining how to ping google and put the data in an influx database (I used this [Jupyter Notebook tutorial](https://www.dataquest.io/blog/jupyter-notebook-tutorial/) for help)

#### June 10

- Attempted fixing ping's output text formatting to get it to work consistently after finding out it doesn't always work
- Worked on the Jupyter Notebook for the Pinging Google project

#### June 11

* Worked on getting job training done; Specifically, I completed the following: 
  * Behavior Based Safety
  * Workplace Harassment Prevention
  * Title IX Training
  * Protection of Minors - Duty to report: Mandated Reporter
  * Protection of Minors - Administrative Practices
  * Employee Safety Orientation
  * Office Safety
  * Slips, Trips, & Falls
  * UAF Laboratory Safety
  
#### June 12

* Continued working on getting job training done; This time, I completed:
  * Hazard Communication
  * UAF Laboratory Safety
  * UAF Chemical Hygiene
  * UAF Hazardous Waste Management
  * Hazard Communication Plan
  * Department Emergency Action Plan
* Got the Google Pinging Project to correctly insert a float of the minimum time value into the influx database

### Week 5

#### June 15

- Added floats for the average and maximum values of the Google Pinging Project
- Edited the Jupyter Notebook to account for all of the changes made on Friday and today so far
- Wrote a paragraph about my work at ACEP for use in ACEP This Week
- Set up the Shelly Cloud app and updated the Shelly 1pm, but the "Advanced Developer Settings" tab never appeared so I couldn't set up MQTT
- Started on the Data Scientist with Python track from DataCamp (did the first couple chapters)

#### June 16

- Completed the next two chapters from the Data Scientist with Python track
- Got the Google Pinging Project properly displaying with Grafana
- Found a problem with the string formatting when increasing the number of pings in a single run and fixed said problem by having the string offset be determined by the end rather than the beginning
- Continued working on the Data Scientist with Python track

#### June 17

- Continued on the Data Scientist with Python track, now 3/5 of the way throught the intermediate course
- Went to the lab and got the in-person lab training from Jeremy

#### June 18

- Messed around with Node-RED by going through some [tutorials from nodered.org](https://nodered.org/docs/tutorials/second-flow)
- Read the papers on Soldering Safety and Electrical Safety Awareness, completing my lab training
- Finished the intermediate course from the Data Scientist with Python track
- Started the Manipulating Data with Pandas course

#### June 19

- Read the documentation on the Solar Test Site maintenance
- Continued working on the Manipulating Data with Pandas course

### Week 6

#### June 22

- Continued working on the Manipulating Data with Pandas course
- Successfully got Shelly 1pm's MQTT enabled and accessed its information from mosquitto.org
- Went out to the solar test site and learned about the maintenance routine

#### June 23

- Worked on making the presentation for my Google Pinging Project
- Got Google Pinging Project to send data to TIG Playground (a remote data location)
- Worked a little more on the Manipulating Data with Pandas course
- Read this article about the sneaky details of [NaN](https://towardsdatascience.com/navigating-the-hell-of-nans-in-python-71b12558895b)

#### June 24

- Wrote a cheat sheet for the Solar Test Site Maintenance
- Finished the slides on the Google Pinging Project
- Gave Rough Draft Presentation of Google Pinging Project
- Brainstormed ideas with Matt and Arsh about how to monitor the devices and network

#### June 25

- Created a diagram of the Solar Test Site
- Researched what makes a healthy network
- Created a list of materials we have and a list of materials we need for the Solar Test Site Maintenance

#### June 26

- Made a program which uses Pythonping to ping a specified website and provides min, max, avg time values to the tig-playground
- Altered the Google Pinging slides to reflect the switch to using pythonping
- Researched good ways to monitor a network
- Altered the Google Pinging jupyter notebook to reflect the switch to using pythonping and the tig-playground
- Added diagram of the AWS Host and Sandia Pi to the Solar Test Site Diagram

### Week 7

#### June 29

- Increased the UDP/IP buffer limit to 8838608 bytes for using the socket listener input plugin for Telegraf
- Updated the Test Site Maintenance cheat sheet to have notes on when to take photos
- Read [Dayne's gist](https://gist.github.com/dayne/5653f864a3de06f238648cb087597512) on autossh
- Installed autossh and read [Ubuntu's manpage on autossh](http://manpages.ubuntu.com/manpages/trusty/man1/autossh.1.html)

#### June 30

- Moved albedometer with Dayne
- Put lab training sheet in the lab binder
- Performed first weekly maintenance at the test site
- Submitted first weekly maintenance data via the google form

#### July 1

- Uploaded the photos of the test site to the Maintenance Photos folder
- Followed a [guide on setting up RSA keys](https://help.ubuntu.com/community/SSH/OpenSSH/Keys) for SSH up to the point where I need to access the server
- Updated Dayne's Solar Test Site debug doc with information about my first weekly maintenance
- Researched ways to monitor if a port is functioning properly

#### July 2

- INDEPENDENCE DAY WEEKEND

#### July 3

- INDEPENDENCE DAY WEEKEND

### Week 8

#### July 6

- Worked on testing_nmap program in Ubuntu VM but ran into issue where 'tcp' didn't appear in all_protocols()'s output
- Worked on testing_nmap program in Windows 10 but ran into issue where 'nmap' has no attribute 'PortScanner'
- Got a version of the program running in Ubuntu VM that claims ports 76 through 80 are all closed (this is likely correct, but I'm not sure yet)

#### July 7

- Performed the weekly maintenance at the solar test site
- Submitted the maintenance data via the google form
- Uploaded the pictures to the Maintenance Photos folder
- Looked for alternate ways to tell which ports are open and which are closed in order to verify that my program works

#### July 8

- Verified that the program correctly determined which ports are open or closed
- Added labels to the Pinging Times dashboard at the TIG-Playground
- Recreated Dayne's "Simple Diagram of Solar PV Test Site" diagram using draw.io
- Created the "Testing nmap" dashboard at the TIG-Playground which successfully receives binary data about the chosen ports (1 means the port is open, 0 means the port is closed)

#### July 9

- Recreated Dayne's "Simple Site Overview" diagram using draw.io
- Figured out how to check that a ping is successful
- Rescaled the Network Overview Diagram to be about the same size as the other diagrams
- Fixed the "Testing nmap" dashboard by deleting the old one and creating a new one within the William folder at the TIG-Playground

#### July 10

- Got ping.py to only add data to the dashboard when the ping attempt is considered a success
- Modified the Monitoring Presentation slides about the pinging program and added slides for my testing nmap program
- Read through a [Wikipedia article on port scanning](https://en.wikipedia.org/wiki/Port_scanner)
- Prepared for and gave presentation on my ping script and my nmap script
- Changed the ping.py's error response to be submitting a ping time of -1ms to Grafana
- Looked into modulizing the nmap and ping scripts to combine them into one project... still a work in progress

### Week 9

#### July 13

- Edited the ping.py code so that it uses the MySeriesHelper class instead of manual json injection
- Edited the nmap.py code so that it uses the MySeriesHelper class, but it claims that "nmap has no attribute PortScanner" (code doesn't work yet)
- Added timestamps as data that is used by nmap.py
- Added timestamps as data that is used by ping.py, but they aren't in the correct working format yet

#### July 14

- Went to the Solar Test Site and performed the weekly maintenance, which now includes cleaning the solar panels if they need it
- Filled out the google form with information on how the weekly maintenance went
- Figured out the problem with nmap.py: Naming it nmap.py caused it to conflict with the module python-nmap. Changed its name to port_check.py and that fixed the problem.
- Changed settings in the "Testing nmap" dashboard in Grafana; It now successfully receives the data from port_check.py

#### July 15

- Fixed the timestamp issue that ping.py had (w/ Arsh's help)
- Changed 'ping.py' to 'ping_test.py' and 'MySeries' to 'pings'
- Edited 'ping_test.py' and 'port_check.py' so they now take info from a yaml file for their target rather than having the target be hardcoded
- Fixed the timestamp issue that port_check.py had (changed the field name from 'Time' to 'time')
- Edited the files so that 'monitor.py' uses 'ping_test.py' and 'port_check.py' as modules (so it's all one united project). However, the time between pings is currently too long.

#### July 16

- Edited 'port_check.py' and 'target.yaml' so that they no longer take a range of ports, but a list of ports instead. They are also now more modular, making adding more ports and targets easier
- Added an example yaml file named 'target.yaml.example' to the git repo
- Edited 'ping_test.py' to be more modular like 'port_check.py'
- Changed 'target.yaml' such that 'ping_test.py' and 'port_check.py' share the same targets

#### July 17

- Overhauled the Pinging Google jupyter notebook so that it would be up-to-date with the latest version of the pinging file, though not with the overall monitoring project
- Overhauled 'target.yaml' so that it's now more user-friendly and less redundant
- Made changes to 'ping_test.py' and 'port_check.py' to match the changes made to 'target.yaml'

### Week 10

#### July 20

- Added monthly maintenance details to the cheat sheet
- Changed my grafana dashboards' times to be in UTC
- Read this [Grafana article on timeseries](https://grafana.com/docs/grafana/latest/getting-started/timeseries/) while trying to find out how to display timestamps in my grafana dashboards
- Read this article on [InfluxDB schema and data layout](https://docs.influxdata.com/influxdb/v1.8/concepts/schema_and_data_layout/)
- Researched ways to optimize nmap performance, including reading this [webpage about scan time reduction techniques](https://nmap.org/book/reduce-scantime.html)
- Read a list of [falsehoods programmers believe about time](https://gist.github.com/timvisee/fcda9bbdff88d45cc9061606b4b923ca) that Arsh posted a link to and which makes me question the sanity of those who actually wrote the date time library

#### July 21

- Performed the weekly maintenance at the solar test site and took the monthly photos as well
- Filled out the google form for the maintenance and copied my photos to the Maintenance Photos folder
- Found [this forum](https://stackoverflow.com/questions/19196105/how-to-check-if-a-network-port-is-open-on-linux) on using the socket module to tell whether a port is open or closed
- Edited 'port_check.py' so that it now uses the socket python module instead of nmap; the program now runs much faster

#### July 22

- Worked on slides detailing what I've learned from my internship
- Tidied up the code by getting rid of redundant code and refactoring some code into helper functions
- Looked into the socket library details to see if it would work correctly with a remote target
- Created the port_check jupyter notebook by essentially copying the code from the py file

#### July 23

- Created a jupyter notebook named Monitor, which is the entire monitoring program except for the yaml file. Still need to add a yaml file somehow.
- Edited the monitoring project files so that the databaseClient info is now in the yaml file rather than hardcoded in
- Edited the jupyter notebook, adding in text to explain most of what the code does (almost done, but not done)

#### July 24

- Uploaded the target.yaml file to the research workspace for the jupyter notebook
- Finished up the text explanations for the jupyter notebook
- Added slide about jupyter notebooks to the slides about what I've learned
- Added slide about network monitoring tools to the slides about what I've learned
- Edited the jupyter notebook so that its database info, like the py files', is taken from the yaml file

### Week 11

#### July 27

- Checked out the stackoverflow discussion and code that Arsh linked me to. The Jupyter Notebook now works for the Get_Ping_Data program, but Get_Port_Data's data claims port 3000 is closed, which I am not sure is true
- Talked with Dayne, Matt, and Arsh about what else I need to do for my monitoring project
- Successfully got VSCode setup on the raspberry pi
- Got the monitoring project up and running on the raspberry pi, now targeting the tig-playground
- Created the outline for the README that will explain how to get the project up and running on a new device

#### July 28

- Performed the weekly maintenance at the solar test site
- Filled out the google form for the maintenance and copied my photos to the Maintenance Photos folder
- Fixed bug where port_check.py attempts to use a closed socket
- Made database_client and yaml wrappers in monitor.py
- Added try/except so the program doesn't end as soon as it loses network connection

#### July 29

- Added a panel to the port checking dashboard for testing new versions of my port checking script without interrupting the pi's data stream
- Add logging such that when port_check does not detect an open port, socket.connect_ex's return value is logged along with the port number and the time
- Changed the logging timestamps from my computer's time to UTC
- Made requirements.txt to make getting setup for running my monitoring program easier

#### July 30

- Added a panel to the pinging dashboard for testing new versions of my monitoring project without interrupting the pi's data stream
- Tried using info from this [stackoverflow article](https://stackoverflow.com/questions/12248132/how-to-change-tcp-keepalive-timer-using-python-script/14855726#14855726) to find a way to enforce a timeout on socket. Still in progress.

#### July 31

- Changed the display of my troubleshooting graphs from using lines to using points; it is now visually obvious whenever there is a disconnect in the stream of data
- Added a try/except for the Get_Port_Data function so it doesn't crash the program when it loses network connection at a specific point in time
- Added a README explaining how to install my monitoring project and get a proper setup for running it
- Fixed Runtime Error problem that crashed the program
- Added exponential backoff for logging so that the log file doesn't get spammed
- Changed targets for (hopefully) good data gathering over the weekend

### Week 12

#### August 3

- Added a hostname tag to the port checking code and dashboard
- Moved the exception handling and logging to the ping_test and port_check files, exponential backoff now doesn't work
- Created a branch on the github repo for working on the post-multithreading stuff
- Got logging and exponential backoff working again, but only problems from ping_test get logged
- Added backoff to requirements.txt

#### August 4

- Performed the weekly maintenance at the solar test site
- Filled out the google form for the maintenance and copied my photos to the Maintenance Photos folder
- Created logger objects (one for ping, one for port). They still don't log properly, but progress has been made (at least mentally).

#### August 5

- Got the logger objects to log to their correct files, but only when they are called to do so in monitor.py
- Read an article on how to [turn a program into a Linux service](https://medium.com/@benmorel/creating-a-linux-service-with-systemd-611b5c8b91d6) (which will make auto-restarting after a power outage easy)

#### August 6

* Worked a lot more on trying to get my logging to work properly. Basically, I found out:
  * What I put in the excepts (from the try/excepts) only gets done one time, right after the exponential backoff
  * Logger objects don't keep their data from file to file
  * The logging.basicconfig settings effect the exponential backoff, so I need to find some way to change the target location of the exponential backoff in each file it appears in to the corresponding log file
  
#### August 7

- Went to the solar test site and got Chris reconnected to the MET Station's Campbell Datalogger
- Got logging to finally send the correct information to the correct log files! However, there is an error where going through the while loop causes each new batch of messages to all be duplicated
- Worked with Arsh trying to fix the duplication bug, but we weren't able to figure it out yet

## Fall 2020

### Week 1

#### August 11

- Had meeting with Dayne and Matt about my future with ACEP
- Went to Solar Test Site and performed weekly maintenance
- Came home and logged my details about the weekly maintenance

#### August 13

- Fixed the duplication bug in my monitoring program
- Tidied up a lot of my code by erasing unnecessary comments and creating the Get_Ping_Logger and Get_Port_Logger functions
- Incorporated TimedRotatingFileHandlers for taking care of old logs

#### August 14

- Added a BackupCount value of 14 to the TimedRotatingFileHandlers, making it so they store up to two weeks' worth of error logs
- Made a monitor service in Ubuntu but it always fails, saying "code=exited, status=2"
- Effectively, my program is done at this point. All I need is to figure out the proper way to get it turned into a service.

### Week 2

#### August 18

- Performed the weekly maintenance at the Solar Test Site
- Came home and logged the details of how the maintenance went

#### August 20

- Created a service for running my maintenance program, but it doesn't work yet

### Week 3

#### August 24

- Worked with Arsh and quickly fixed the problems plaguing my service; it's now fully functional!

#### August 25

- Went to the Solar Test Site and performed the weekly maintenance as well as the monthly tasks
- Came home and logged the details about the maintenance

#### August 27

- Checked to make sure monitor.service is still working properly (it is!)
- Pushed monitor.service's changes to github
- Added steps for making a service to the README
- Edited the dashboard on Grafana to make it better for looking at (still needs work)

### Week 4

#### September 1

- Went to the Solar Test Site and performed the weekly maintenance 
- Came home and logged the details about the maintenance

### Week 5

#### September 8

- Went to the Solar Test Site and performed the weekly maintenance
- Came home and logged the details about the maintenance

### Week 6

#### September 15

- Went to the Solar Test Site and performed the weekly maintenance 
- Came home and logged the details about the maintenance

#### September 16

- Looked into how to setup an alert
- Brainstormed when alerts should go off and when they shouldn't

#### September 17

- Looked deeper into how to make\edit an alert
- Set up an alert for port 8086 on my monitoring software as a test

### Week 7

#### September 22

- Went to the Solar Test Site and performed the weekly maintenance
- Came home and logged the details about the maintenance

#### September 23

- Looked at the data for the Solar Site alerts and formed a proposal about changing the alerts

#### September 24

- Gave my proposal and received feedback about looking into working with Grafana averages over time

#### September 25

- Title IX Training

### Week 8

#### September 29

- Went to the Solar Test Site and performed the weekly and monthly maintenance
- Came home and logged the details about the maintenance

### Week 9

#### October 6

- Went to the Solar Test Site and performed the weekly maintenance
- Came home and logged the details about the maintenance

#### October 8

- Looked into how to get moving averages in Grafana and came up with a couple of links

## About Me

Currently, I am a college student working toward a Bachelors Degree in Computer Science. Though I do not have specific plans for what I intend to do after obtaining my degree, I intend to pursue a job in the Computer Science career field to further my skills following graduation.


### Off-Topic
All things considered, writing what needs to be added to the website on the website is very meta
