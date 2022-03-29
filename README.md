
# CVE-2022-22948
## Information Disclosure in VMWare vCenter

-   Pentera’s research group discovered a vulnerability in VMWare’s vCenter Server program affecting VMWare’s software installed in 500,000 organizations worldwide responsible to manage their most critical systems
-   Our findings were proactively reported to VMWare and were released under CVE-2022-22948
-   Patch and additional info are available on [VMWare’s Advisory site](https://www.vmware.com/security/advisories/VMSA-2022-0009.html)

## Scanner

The scanner is designed to check whether the file in question has write access to the “cis” group, and is there any user in that group that has shell access to the host. 

For further explanation about CVE-2022-22948, please refer to our site [here](https://www.pentera.io/blog)

## Prerequisites
•	Credentials for a Linux (PhotonOS) vCenter host

•	Shell access 

## Usage

1. Download the scanner to your machine
2. Execute to following commands
```
chmod 777 ./CVE-2022-22948_scanner.sh
./CVE-2022-22948_scanner.sh
```

Results:
* Vulnerability found: "Host is vulnerable to CVE-2022-22948"
* Vulnerability not found: "Host isn't vulnerable to CVE-2022-22948"

## DISCLAIMER: 
The code described in this advisory (the “Code”) is provided on an “as is” and
“as available” basis may contain bugs, errors and other defects. You are
advised to safeguard important data and to use caution. By using this Code, you
agree that Pentera shall have no liability to you for any claims in
connection with the Code. Pentera disclaims any liability for any direct,
indirect, incidental, punitive, exemplary, special or consequential damages,
even if Pentera or its related parties are advised of the possibility of
such damages. Pentera undertakes no duty to update the Code or this
advisory.
CVE-2022-22984 readme.md
Displaying CVE-2022-22984 readme.md.
