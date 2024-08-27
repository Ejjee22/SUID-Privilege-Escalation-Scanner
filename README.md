# SUID-Privilege-Escalation-Scanner

This script automates the process of discovering binaries with SUID permissions on a Linux system and checks if they are vulnerable to privilege escalation using the [GTFOBins](https://gtfobins.github.io/#) database.

## Overview
SUID (Set User ID) is a special type of file permission that allows a binary to be executed with the privileges of the file's owner, often root. While SUID binaries can be necessary for some system functions, they also pose a security risk if they can be exploited for privilege escalation.

[GTFOBins](https://gtfobins.github.io/#) is a curated list of Unix binaries that can be abused to bypass local security restrictions in misconfigured systems. This script leverages the GTFOBins website to automatically determine if any SUID binaries on your system are known to be exploitable.
