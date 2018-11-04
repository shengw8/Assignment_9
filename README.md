# Codepath Assignment 9 Write-up

# Which Honeypot(s) you deployed 
Since I encountered a lot of problems during the installation of the mhn and the honeypot, I only deployed one honeypot, which was 
+ Ubuntu - Dionaea with HTTP

# Any issues you encountered 
+ At first, I did not know I have to install the Modern Honey Network in the Google Cloud Platform. 
+ There were problems with older mhn on the github links provided in the spec. I find another one on the "https://gihub.com/threatstream/mhn".
+ After executing "sudo ./install.sh" for the mhn server, I was experiencing problems accesssing the external IP Address. I could not reach the log in page. 
+ After accessing the map, I've been receiving attacks but when I went to the Attack page, none of the attacks was shown in the list. And then I went back to the map, every attack was gone. 

# A summary of the data collected
+ Creation Time for the mhn-admin server: Nov 2, 2018, 7:00:50 PM
+ Creation Time for the honeypot: Nov 2, 2018, 8:24:59 PM
+ I received 8327 record of attack. 
 
 
 Here's a json file of all the attacks in more details.
# Any unresolved questions raised by the data collected
+ I'm still unable to access the external IP Address by just simply clicking it. But when I copied it into another tab in the browser, and everything magically works.
