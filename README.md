# Lenovo-L440-20AS-OPENCORE
An updated Opencore EFI based on the Opencore-Mod with an additional fixes to get sleep working,
probably will only get Tahoe Support and then that's gonna be it from me.

# How to Use: 
1.Download a copy of this repo


2.Extract to the Root of your USB



3. If you have the normal intel WIFI, copy the Wifi Patch into EFI/OC and rename as config.plist
Rename the other one to configbak.plist


4.reboot and install macOS as normal



5.Install and Open Opencore Legacy Patcher, and it should ask for both the Graphics and Modern Wireless



6.When it is done, DO NOT REBOOT! open terminal and run 'sudo diskutil mount /dev/disk0s1' (if you installed into 
the internal SSD)

Copy the EFI Folder into that new EFI drive, and grab the Post Wifi Patch and drop it in as config.plist

(rename the current one as WifiPatch.plist, you will need it for updates!) 

thats it! ive added the extra fixes to get sleep working! so once GPU and Wifi are patched, it should just work!
