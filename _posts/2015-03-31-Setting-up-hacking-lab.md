---
layout: post
title: Setting up a Pen Testing/Hacking Lab Network 
comments: true
image:
  feature: sample-image-5.jpg
  credit: WeGraphics
---

###Installation & Configuration:

I used Oracle's VirtualBox for Mac to set up my hacking lab. It is the world’s most popular cross-platform virtualization software that enables you to run multiple operating systems on your Host OS. Here is the [Download link](http://download.cnet.com/VirtualBox/3000-2094_4-145711.html). Once we have installed the VirtualBox, the process is half done. <br/>

<br/>The next step is to setup the system from where we will perform the actual hacking.  For this purpose, I chose Kali Linux. Kali is one of the most widely used penetration testing operating system by security professionals because: <br/>

* It has all the relevant hacking tools pre-installed
* It is linux based

You can download the iso image from [here](https://www.kali.org/downloads/). <br/>


<br/>Setting up a VM on VirtualBox is pretty easy. You can refer to this quick video on how to setup Kali on VirtualBox. <br/>

<iframe width="560" height="315" src="https://www.youtube.com/embed/Rka5MqnCn1E" frameborder="0" allowfullscreen></iframe>

<br/>
<br/>Now the next step is to setup a target operating system. I used both Windows XP and Windows 2000 server for this purpose. You will need a bootable Windows XP SP3 and Windows 2000 server iso for that. You can easily download them from Microsoft's website. <br/>
Refer to this video for setting up Windows XP on VirtualBox. <br/>

<iframe width="560" height="315" src="https://www.youtube.com/embed/DeGRIWwd_Ao" frameborder="0" allowfullscreen></iframe>

<br/>
Now we are all set to conquer the world of hacking! :D
<br/>
<br/>Here are some of the major advantages of using virtual machine:<br/>

* You can test all the viruses and RATs without any fear as your base operating system will not be affected.
* You can test different servers and applications easily without affecting your base operating system.
* In case the Virtual machine gets corrupted, you can re-install it.




