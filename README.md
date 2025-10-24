# CheckMK
Documents I've written for my CheckMK Lab Raw Edition 

# [Installing CheckMK on RHEL 9](https://github.com/Jere557/CheckMK/blob/main/Installing%20CheckMK%20on%20RHEL%209.docx)
﻿Author: Jeremiah Holland Date:10/24/2025 <br>
<b>This guide lists out the steps on how to install and configure CheckMK on RHEL 9.  <br>
```
Steps:
  Pre-Reqs
  Required Documentation
    Installation
    Firewall
    Download the software
      Download CheckMK via wget
      Verify the File Hash
      Install the CheckMK Pachage software
      Verify Version
  Create Site
    Create a Named site
    Configure Site
      Web GUI
      Distributed Monitoring
      Exit out of site configuration mode
  Start the Site
  Log into Site 
  ```

# [Importing Nodes into CheckMK](https://github.com/Jere557/CheckMK/blob/main/Importing%20Nodes%20into%20CheckMK.docx)
﻿Author: Jeremiah Holland Date:10/24/2025 <br>
<b>This guide lists out the steps on how to monitor the CheckMK host as well as adding in a remote Linux server.  <br>
```
Steps:
  Pre-Reqs
  Required Documentation
    Install Agent on CheckMK Server via GUI
      Download the Agent
      Install the Agent via yum install
    Add the CheckMK Sever as a host to Monitor
      Configure and Scan a Host
      Determine which resources should be monitored
      Confirm Changes
    Reviewing A Monitor
    Installing the agent on a Remote Server
      Use SCP to transfer agent file to remote host
      Open Fireall Port on Remote Server
      Install software on remote server
    Add Remote server as a Host to Monitor
      Select Services and Resources to Monitor
      Confirm the Changes
  ```
