---
title: "Virus Sort"
date: "2023-07-02"
author: "c0dex"
---

A tool to sort a malware collection. Its still in developement and in a very initiall phase.


### Features

Here are listed the potential features just to track the progresses.

- File Management:
    - [X] Calculate hash (MD5, SHA1, SHA224, SHA256, SHA384, SHA512) of files 
    - [X] Rename files based on their hash code
    - [X] Move files (the file name is its hash code) to the respective folder following the pattern: files with hash starting with `00` go to the folder `0\00\`
    - [ ] Move to a different folder files defined as benign or not into the VirusShare or VirusTotal database
    
- Reports:
    - [X] Connect with VirusShare API and get the file report in JSON format
    - [X] Connect with VirusTotal API to get the report in JSON format
    - [ ] Automatically trigger the update on a file report. Need to check this possibility
    - [ ] Parse JSON objects to save into a SQLite database
        - [ ] Implementation of classes to accomodate the JSON content

- Other:
    - [ ] Save GUI configuration including private API keys


### Screenshot

{{< image src="vs-2023-07-01.png" alt="Virus Sort main screen" position="center" >}}

### SQLite database 

{{< image src="vs-sqlite-2023-07-01.png" alt="" position="center" >}}