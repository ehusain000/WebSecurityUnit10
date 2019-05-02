# WebSecurityUnit10

Week 10 - Honeypot

Time Spent: 16 Hours

Objective: Setup honeypot and understand how attacks are carried out using it.

Honeypots Deployed: Ubuntu - Dionaea with HTTP

Issues Encountered: Setting up the virtual machine instances and making sure the firewall settings are correct.

Summary: - 34 Attacks
          -Top Attacked Port 9099 (6 Times)
          - Top Attacked IP 118.172.223.96



REQUIRED

Overview & Setup

To set up a honeyspot I first made a GCP account and then created a virtual machine instance using the commands provided and the gcloud. Then once I had the MHN-admin set up I created an instance of honeypot (mhn-honeypot-1) to complete this assignment. The GIF below summarizes this procedure

![Week10_1](https://user-images.githubusercontent.com/32075350/57054822-09988d00-6c65-11e9-8ed1-baa288743f93.gif)



Demonstration 

![Week10_2](https://user-images.githubusercontent.com/32075350/57054852-2d5bd300-6c65-11e9-9765-cdc2c3e06149.gif)

nmap was used to scan the networkmap 

A session.json file is attached to this repository which has 1088 record.
