# bash


#!/bin/bash
NOW=$(date +"%Y-%m-%d-%T");
LOGFILE="log-$NOW.txt";
/usr/bin/arp -a > /home/cwc/html/logs/$LOGFILE;
