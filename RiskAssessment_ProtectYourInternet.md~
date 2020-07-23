# Hiding From the Internet -- Making a Plan
 <sup>* Information largely *taken* from the EFF</s> [^1]

[^1]: <sub>pretty much copy/pasted or slightly changed the wording from their website, so yes, this is plagiarized material pretty much...  
  *meant for personal use.</s>


1. [What do you want to hide?](#what-do-you-want-to-hide)
2. [Who do I want to protect it from?](#who-do-i-want-to-protect-it-from)
3. [How bad are the consequences if I fail?](#how-bad-are-the-consequences-if-i-fail)
4. [How Likely is it That I will Need to Protect it?](#how-likely-is-it-that-i-will-need-to-protect-it)
5. [How Much Trouble am I Willing to go Through to try to Prevent Potential Consequences?](#how-much-trouble-am-i-willing-to-go-through-to-try-to-prevent-potential-consequences)
6. [Security Planning as a Regular Practice](#security-planning-as-a-regular-practice)

### What do you Want to Hide? {#what-do-you-want-to-hide}
An ***asset*** is something you value and want to protect. In the context of digital security, an asset is usually some kind of information. for example, your emails, contact lists, instant messages, location (current and past), and all files you come into contact with are all possible assets. Your devices may also be assets.

- Make a list of your assets: data that you keep, where it's kept, who has access to it, and what stops others from accessing it.
: Notable entities you should be wary of is large companies such as Google or Amazon. These two companies alone own an absurdly large portion of the services available on the internet.  
<br/>
Also be wary of those physically near you, think about what you may have locally accessible via your phone or laptop, is it protected from people that can grab your device out of your ownership? What's your solution if your device is stolen?

### How bad are the Consequences if I Fail? {#how-bad-are-the-consequences-if-i-fail}
There are many ways that an adversary could gain access to your data. for example, an adversary can read your private communications as they pass through the network, or they can delete or corrupt your data.<br/>  
the motives of adversaries differ widely, as do their tactics. A government trying to prevent the spread of a video showing police violence may be content to simply delete or reduce the availability of. In contrast, a political opponent may wish to gain access to secret content and publish that content without your knowing.<br/>
Think about every law you have broken on the internet, or every law you have talked about breaking on the internet.. Or any photos of broken laws to that point. Living in the U.S.A, all your information is intercepted and stored on servers for potential review.<br/>
Security planning involves understanding how bad the consequences could be if an adversary successfully gains access to one of your assets. To determine this, you should consider the capability of you adversary. For example, your mobile phone provider has access to all your phone records. A hacker on an open Wi-Fi network can access your unencrypted communications. Your government might have stronger capabilities.

- Write down what your adversary might want to do with your prvate data.
: 

### How Likely is it That I will Need to Protect it? {#how-likely-is-it-that-i-will-need-to-protect-it}
***Risk*** is the likelihood that a particular threat against a particular asset will actually occur. It goes hand-in-hand with capability. while your mobile phone provider has the capability to access all of your data, the risk of them posting your private data online to harm your reputation is low.<br/>
It is important to distinguish between what might happen and the probability it may happen. For instance, there is a threat that your building might collapse, but the risk of this happening is far greater in San Francisco (where earthquakes are common) than in Stockholm (where they are not).<br/>
Assessing risks is both a personal and subjective process. Many people find certain threats unacceptable no matter the likelihood they will occur because the mere presence of the threat at any likelihood is not worth the cost. In other cases, people disregard high risks because they don't view the threat as a problem.<br/>

- Write down which threats you are going to take seriously, and which may be too rare or too harmless (or too difficult to combat) to worry about. 
: 

### How Much Trouble am I Willing to go Through to try to Prevent Potential Consequences? {#how-much-am-i-willing-to-go-through-to-try-to-prevent-potential-consequences}
There is no perfect solution for security. Not everyone has the same priorities, concerns, or access to resources. Your ***risk assessment*** will allow you to plan the optimal strategy for you, balancing convenience, cost, and privacy.<br/>
For example, an attorney representing a client in a national security case may be willing to go to greater lengths to protect communications about that case, such as using encrypted email, than a mother who regularly emails her daughter funny cat videos.<br/>

- Write down what option you have available to you to help mitigate your unique threats. Note if you have any financial constraints, technical constraints, or social constraints.
: 

### Security Planning as a Regular Practice {#security-planning-as-a-regular-practice}
Keep in mind your security plan can change as your situation changes. Thus, revisiting your security plan rfrequently is good practice.

# How far are you Willing to go? 
 <h2><center>* Computers</center></h2>

1. No Protection ***"I'm the Pull-Out King!"***
2. Simple Security Measures
3. Moderate Difficulty Actions
4. Hermit Level Security
<br/>
<br/>

### No Protection ***"I'm the Pull-Out King!"***

The Internet is a large and dangerous place, think about it like the ocean, or an ice berg. You only see the very tippy-top of that bad-boy, and the rest is all mystery. You don't know what's going on in there, is any of it a threat to you? When you access a website, you are talking to severeal different computers and companies throughout the world, and without any protection, or action on your end. They will see anything and everything you do on the internet. 
<br/>
<br/>
Would you trust a stranger with your porn history?

### Simple Security Measures

Simple security is the base minimum. The miniminum, in this case, however, is miles better than nothing.  

#### Browser Add-ons
Any modern web browser should allow add-ons, or extensions. A strong recommendation would be to install something like Ublock or Privacy Badger. These use blacklists to avoid nefarious IP Adresses <sub>(websites, or elements on websites, visible or not)</s>  

#### Firewalls
While no longer a super important step to security, it does matter very much if you plan to install or access any services that aren't 100% transparent with you. Examples would be sharing files between computers on a local network, or installing any app from anywhere other than your designated app store/center.
<br/>
Firewall security will vary for every OS.
<br/>
<br/>
On **Windows**, I would highly recommend **TinyWall**. It's a simple systray app that will block all incoming internet by default. This is important, this means that nothing will be allowed in unless you explicitly allow it yourself.
<br/>
<br/>
On **OSX**, the system firewall should be good enough for operation. Upsettingly however, the firewall is turned off by default. All you have to do is go into the **Security and Privacy** section of your settings and then unlock and turn on the firewall! Voila! Off to the races.
<br/>
<br/>
On **Linux**, It is considered generally safe to leave alone, as the ports are all configured to off by default. To be sure though, as any app once installed, can activate these ports, we're going to get **UFW**. You should be able to grab it from your distribution's package manager. When trying to install you may notice two similar packages; UFW takes less power to run than GUFW, the only difference being GUFW gives you a graphical interface to work with. Once installed, the best measure is to insert these commands into your Terminal:
<br/>

```
sudo ufw default deny

sudo ufw allow from 192.168.0.0/24

sudo ufw limit ssh

sudo ufw enable
```

Then all you have to do is check that it's still running!

```
sudo ufw status
```

#### Encryption in Communication
When communicating on the internet, it is important to be aware of what channels you are going through, as well as who can see it. A lot of more modern e-mail clients and instant messagers will provide encryption of some sort. This however is never a true guarantee. For instance, Google claims to encrypt all of your emails and chats, but they still have the capability to open up and view those very texts, as well as deliver them to any respective government.
<br/>
When speaking to your friends and family it is all good and well to use your email provier's encryption, but don't for any second believe that they won't give it up if it contains incriminating information or ***tag*** it for ***fingerprinting***.
<br/>
***fingerprinting*** is generally a term to define when a website or service tries to identify you through all the information it can gather from your web browser (or other windowed internet-application), being your Location, IP Address, Web Browser, Web Browser Version, Operating system, GPS Signal, any access granted to the microphone or webcam, on, and on.... (We give our web browsers access to our entire computers these days...)
<br/>
In my case, I like to use that word to define anyone or anything on the internet trying to harvest data about you or your device without permission or warning.
<br/>
Companies like Google or Amazon will gladly sell all of your information to ad agencies for the sake of making easy money. If you ever wonder *"How do companies stay afloat with all these free services, just as good as they paid ones?"* It's because they aren't free, you're the product, and the agencies are using these services as a way to buy you out!
<br/>
<br/>
So, what can you do?
<br/>
Don't worry about it too much! Don't want people stealing your conversations? Try finding an e-mail service that YOU pay for, and if you ever have to send sensitive information over the internet, encrypt it yourself!

### Moderate Difficulty Actions
Moderate security could be considered the "Goldilocks Zone" of security, it's not absurdly hard, but it will be decent enough to keep yourself free of local government, ISPs, and peeping toms.

#### GPG -- Encrypt on your own!
GPG, or Gnu Privacy Guard, is a F.O.S.S program that one can use to essentially password protect their communications, files, or traffic! ***How do we do it??***  
  
On **Windows** you would use a software like **Gpg4win**. This is an app that refers to itself as not a app, but simply an installation package [for other packages]. This is a group of packages put together to help apply encryption to all your communications. On it's website it lists these options as:  

* GnuPG
* Kleopatra
* GNU Privacy Assistant (GPA)
* GnuPG for Outlook (GPgOL)
* GPG Explorer eXtension (GpgEX)
* Claws Mail  

These additional add-ons are actually pretty convenient! They allow you to create a more fluid experience with your desktop and GPG!  
**Kleopatra** as described by the website's supplied PDF as, *"The central certificate administration of Gpg4win, which ensures uniform user navigation for all cryptographic operations."* Broken down, it's a key-handler, so it'll be kind of like a password manager, or a identity library.  
**Gnu Privacy Assistant** is also present, which seems to be the same thing as Kleopatra, simply by the naming scheme this one seems safer.  
**GnuPG for Outlook** and **GPG Explorer eXtension** are add-ons to the system. The first allowing you to sign and encrypt messages, and the latter for doing the same in your **File Explorer**.  
**Claws Mail** is a lightweight, GPG enable*-able* e-mail client comparable to **Thunderbird**. *<sub>Which you can also use with encryption</s>*  
  <br/>
**Setting up after installation** is made pretty easy, all you have to do is (in the example we will be using..) open **Kleopatra** from the Start Menu. From the start, you will get an empty box. All you have to do is go to File→New Certificate. This will open a dialog box for you to pick between OpenPGP or X.509, I recommend you go with OpenPGP for the first time. You will be greeted with a Certificate Creation Wizard, first, it will ask for your name, email and a comment. If you are using this for your work (usually computer development, or banking or something like that, you can fill these honestly. Otherwise, there is no rule saying you have to fill all of these in or if they have to be your real name; which is good for anyone trying to evade laws, if in fact you ever are cracked (however extremely unlikely to ever even become a problem).  
The next window will show you your information, and then prompt you to create the key. Next you will have to enter a passphrase for said key. It is best to enter the password into the prompt, but never save it in any clear(unencrypted) text files on a device connected to any network (save it on a USB!).  
After all this, they key will begin generation. In order for this process to complete, you need to create entropy for the computer. This means clicking and typing all around, to encourage more data to be set into and out of the CPU to help it generate a key. This creation process, however, provides you with a nice little text box to type away gibberish in to your heart's content! Or at least until the generation is completed.  
Once the creation is completed, you will then be able to backup, send, or upload your key pair or certificate to other places for sharing and safe keeping. It is best to share your certificate, but never share your key pair with ***ANYONE***.  
<br/>
On **OS X** there is a similar package called the **GPG Suite**, curated by, funnily enough, **GPGTools**. Installation will be close to exactly the same as on Windows, just prettier.  
<br/>
With **Linux** it's a little bit of a more different experience, but a lot simpler! You simply have to install the <code>gnupg</code> package, and hopefully it'll give you all the dependencies, if not, try installing <code>pinentry</code>. After that, you can begin creation! Type in <code>$ gpg --full-gen-key</code>, this will prompt you for your name, e-mail, and any comments. With any other questions, the default is plenty fine. Once generation begins, simply click and type around the desktop to help it make the keys! Once it's generated, it is saved to your home directory and accessible to you throughout your system!  
One thing to note with Linux, is that any application that supports GPG requires setting up, though there is plenty of documentation on the internet about how to do it with any service you may please.  
  
#### VPN Services and Network Routing  
**VPN** or **Virtual Private Network** refers to a secondary router, or server, that you can connect to before hitting your ISP or any other servers or websites on the internet. Getting a VPN service is much more recommended by myself, as it's easier maintenance for you, but also, each service provides instructions on how to set up their connection differently, and a lot of them provide failsafes that OS's don't seem to carry (like turning off the network if the VPN disconnects).  
  
Another direction to take this in would be with Network Routing, the most common service known as **Tor**. This is an abbreviation for **The Onion Router**. What it does, is it creates a network of interconnected devices, all sharing data and traffic, making it hard for any action or click be traced back to any one person. To use this, it is highly recommend by everyone in the industry to stick with the TOR Browser, an application based off of Firefox made specifically to ensure anonymity (look back to fingerprinting).

### Hermit Level Security
This section is for people that have something to hide. Are you a whistle blower? Are you looking to disrupt society a bit, and don't wanna leave a cookie trail? Go no further (or do if you dare) than this section here.  
<br/>
---Work in Progress---  
<br/>
 <h2><center>* Phones</center></h2>

1. No Protection ***"Bro, it's just a phone!"***
2. Simple Security Measures
3. Hard Mode Security
<br/>
<br/>
### No Protection ***"Bro, it's just a phone!"***
I could say the same things I said in the **computer section**, but phones are worse. When you're using a phone, it gives out blanket permissions. All the apps you're using have constant access to all the peripherals they ask for. Use Facebook or Google at all on your phone? (If you use an Android phone, it has Google on it.) Those apps alone have access to all of your inputs, *microphones, cameras, files, text messages, phone calls, etc.,*.  
<br/>
I mean, you should know by now that when something is for free, they are selling your data and information, so imagine who could get ahold of that information with simple a hefty bill-book!
<br/>
### Simple Security Measures
Simple security in this section *feels* like the bare minimum, but realistically, phones are the easiest to lock down (or the most pointless... due to reasons you can read about elsewhere). All you have to do really is simply lower your network traffic and route it somehow to prevent IP tracking.  
<br/>
#### Network Routing
To prevent any of your traffic becoming someone elses information, through your ISP, install **Blokada** from **F-Droid**, as it's the open-source version, and allows more protection. Then, set it up!  
anecdotally, I also use a **VPN** service that provides proxies for subverting blocklists and such, but it's also good for communication apps, like **Telegram** which tout encryption and no logs, but also, the environment it's developed in (Russia), it can be a little hard to trust fully. Sending it through a proxy will effectively change the tagged location when used with **Blokada**, as to protect UDP leakage.

