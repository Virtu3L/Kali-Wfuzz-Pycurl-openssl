# Kali-Wfuzz-Pycurl-openssl
This is a bash script adapted for Kali Rolling, who will build pycurl with openssl for use wfuzz

# Original Bash Script
https://github.com/adon90/openssl_wfuzz

# How to use?
- Create a non root user.

adduser --home /volken volken

usermod -a -G sudo volken

chsh -s /bin/bash volken

- Logout your root session and login with your new user

- Once in your new non root user clone my repository

cd /opt

git clone https://github.com/Virtu3L/Kali-Wfuzz-Pycurl-openssl.git

- Enter inside the directory clonned, and run the bash script with sudo

cd Kali-Wfuzz-Pycurl-openssl

chmod +x wfuzzpycurl-kali.sh

sudo sh wfuzzpycurl-kali.sh

# ENJOY with Wfuzz!
