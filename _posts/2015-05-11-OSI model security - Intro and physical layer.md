---
layout: post
title: Understanding OSI Model Security - Physical Layer
comments: true
image:
  feature: sample-image-5.jpg
  credit: WeGraphics
---

In a series of posts starting from this one, I am going to talk about some well-known vulnerabilities of each layer of the OSI model and few security measures to reduce the risk of attack. <br/>

### OSI Model

These days, internet connection has become as popular as having a car or a bicycle. However, this 'internet connection' is all it takes to exploit a well-known vulnerability. The task of securing a computer itself can be a daunting one, imagine the task of securing a network!! In order to simplify this task, IT administrators need a starting point and this starting point should be understanding the OSI model. The OSI model breaks the network into easily understood components that can be secured individually.<br/>

<br/>This is a cool video that gives you a great explanation of each layer of the OSI model.<br/>
<iframe width="560" height="315" src="https://www.youtube.com/embed/-6Uoku-M6oY" frameborder="0" allowfullscreen></iframe><br/>


## Physical layer Security
Physical layer defines the physical properties of the network, such as voltage levels,
cable types, and interface pins. Exploiting the Physical Layer could suggest some type
of physical action, like disrupting a power source, changing of interface pins, or the
cutting of cables. The most common exploits on the physical layer are discussed below. <br/>

### Keylogger
A Keylogger is a malware which could be a software program or a hardware device created to capture every keystroke that the user makes. Keylogger basically captures every single number and letter that you type which means it can log every single website that you visit, every single email you receive/send and every document you create. Keyloggers are sometimes used for legitimate purposes such as an employer trying to monitor its employees' activities or a parent trying to monitor their child's internet usage. But keyloggers are for the most part used with malicious intent so as to capture a victim's personal information such as user names, passwords, credit cards, bank account numbers and other sensitive information. Software keyloggers can be delivered to your computer like any other malware over the internet. Hardware keyloggers have to be physically installed on your computer using a keylogging device.<br/>

<br/>Below is an example of a hardware keylogger that can be installed on a computer.<br/>
<br/>![IDE setup]({{ https://srujanaputtagunta.github.io/ }}/assets/images/post5/Keylogger-hardware.jpg)<br/>

<br/>The following log file shows the information that the keylogger captured. <br/>
<br/>![IDE setup]({{ https://srujanaputtagunta.github.io/ }}/assets/images/post5/Keylogger-software.jpg)<br/>


#### Measures to prevent ourselves from keylogging attacks:<br/>
1. Be careful what you download and run. If your computer becomes compromised, the malware  may include a keylogger or function as a Trojan that downloads the keylogger along with other harmful software.<br/>
2. Install antivirus software. Most antivirus softwares already have the well-known keyloggers in their database. So the best method is to install an antivirus software and keep it upto date.<br/>
3. One-time passwords and two step authentication. Since the main purpose of keylogging is to intercept sensitive information, the best way is to prevent these attacks by setting up one time passwords and two step authentication. One example is to make use of mobile phone text messaging systems that are registered with the banking system and receive a one-time PIN-code as a reply. The PIN is then used together with the personal code for authentication. <br/>
	
	
### Lock Picking
If you are wondering how secure your lock is, let me tell you the answer - any lock can be opened. It is only a matter of how long it takes, how much skill and what tools are used - just like hacking. Lock picking is also a hacker skill. Check out DefCon, which is a yearly hacker conference that has presentations and seminars devoted to lock picking. To see how quickly some individuals can bypass a lock, check out this video from Defcon 20 <br/>

<br/>
<iframe width="560" height="315" src="https://www.youtube.com/embed/Um3l47yyCEQ" frameborder="0" allowfullscreen></iframe>
<br/>

	
<br/>In addition to getting a better lock (higher quality, more pins, higher security design), these are a couple of suggestions to slow down the attacker<br/>
-Install a deadbolt in addition to your primary lock. Deadbolts are more resistant to lock picking than traditional door locks and a second lock requires a would-be thief to work twice as hard.<br/>
- Install the lock upside down, so the jaggy side of the key goes in facing down instead of up.  They are harder to pick upside down, and my experience is the same.<br/>
	

### Cutting cables
Tampering with someone's cables outside their office or residence can cause a disruption or denial of service condition. Additional protection should be added around those cables or fibers to prevent damage. A protection system should be in place where all the cables are sealed inside a metal conduit. There are also certain circuit-based alarms available which notify the admin when the circuit is opened or closed. Motion detection alarms are also available in the market. These are usually placed around the perimeter to detect when somebody walks in a door or enters through the window. By installing an Uninterrupted Power Supply (UPS) to your system you can avoid many unrecoverable power associated problems. Add an UPS to your critical system and when power is interrupted your UPS will give you time to perform an orderly shutdown. <br/>
