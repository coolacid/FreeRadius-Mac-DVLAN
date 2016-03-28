# FreeRadius-Mac-DVLAN
Barebones FreeRadius Config for Mac Based Dynamic VLANs

This works for me on the ubiquity UBNT platform - no expectation it will work for you.

Edit two files:

users: This defines the WPA Enterprise usernames and passwords, you can also set VLANs here
mac2vlan: Defines a VLAN based on it's MAC address post authentication from users file
