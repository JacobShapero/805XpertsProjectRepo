# 805XpertsProjectRepo

## Splunk Setup Instructions ##

Splunk Tutorial: Getting Started Using Splunk | Splunk.
https://www.splunk.com/en_us/blog/learn/splunk-tutorials.html

Install Splunk Enterprise from Free Trials and Downloads | Splunk.
https://www.splunk.com/en_us/download.html

Then, open Splunk Enterprise (should be a website).
Click in the top right, ‘settings’, then click licensing.
Click ‘Change license group’.
Click ‘Free license’.
There you go! You have Splunk.

– OR –

Download through docker.
splunk/splunk - Docker Image | Docker Hub.
https://hub.docker.com/r/splunk/splunk/

## Creating Splunk Reports ##

Run Splunk Enterprise locally.
Navigate to "Add Data" and upload your selected dataset.
Navigate to "Search & Reporting".
Navigate to "Reports".
Begin writing SPL queries. Example on dataset 1: source=<source> host=<host> | stats count by result.uri
