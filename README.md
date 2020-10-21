# Using your Raspberry Pi as a rogue access point

So I bought a new Raspberry Pi 3 B+ and and a ESP8266 nodeMCU dev board, some wires and a bread board hoping to automate my home this quarantine, but I eventually got bored of it...assembling all the hardwre, configuring it, embedding it to my home's power control board blah blah blah. So then I came up with an idea to put my new linux skills to use and ta-daa! whats more exciting than testing out new stuff. Then I remembered that I read an article some days back about how to make a rogue WiFi access point with a Raspberry pi. This came quite at the right time because I was looking for a MIFI that I could use because I got tired of having to hotspot from my phone all the time. Plus it also drained a lot of my phone's battery power. So after experimenting with a couple of the resources I found online (whic was A LOT and many of them didn't work for me). I along with the help of a few tech savvy friends wrote a script to automate that for me and anyone else who might stumble across this project. At the time of writing I was using a raspbian buster. However I am confident it will work for raspberry pi jessie and beyond stretch since they all have sort of the same "OS layout".

The install.sh script will turn your raspberry pi into a wifi access point. There a lot of tutorials online about how to turn your raspberry pi into an access point, however after experimenting with a bunch of them, I finally had one that worked for me after countless tweaking.

This version assumes that you are providing internet to the rpi through a dialup USB modem stick and then routing the packets from that to the wlan interface. By so doing, devices connected to the access point will have connectivity to the internet without necessarily being connected to the USB modem.

You can also run the uninstall.sh file to undo all the changes and your raspberry pi will go back to its default setting.

Until next time...

-B
