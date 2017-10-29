## Remote Duck Repo

# Payloads

# YoutubeTabPrank

This payload runs a python script that has a While loop that continually opens Lean On (or your favorite Youtube Video) in new tabs

# How to Add Payload to Ducky

- Remove the MicroSD card from the Rubber Ducky and add to the USB adapter
- Insert into PC and check for it's file location (On Mac and Linux)
- Typically it will be stored under /media/somewhereHere
- cd to the loction where your prank.txt file is
- run "java -jar duckencoder.jar -i prank.txt -o /media/SDCardName/inject.bin"
- Safely Remove the USB Drive
- Ready to go!

# DuckRAT

This payload grabs private SSH keys and uploads it via SCP to a remote server. 