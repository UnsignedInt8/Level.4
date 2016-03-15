# Level.4(iOS) 5(OS X)

An app for protecting your iOS/OS X network traffic.

LightSword is a server program written by Node.js. And to use Level.4/5, you should install LightSword on your server. It's very simple! 

1.Installing

```
# Using Ubuntu
[sudo] apt-get update -y
[sudo] apt-get install curl -y

[sudo] curl -sL https://deb.nodesource.com/setup_5.x | sudo -E bash -
[sudo] apt-get install -y nodejs
[sudo] npm install lightsword -g

# Using Debian, as root
[sudo] apt-get update -y
[sudo] apt-get install curl -y

[sudo] curl -sL https://deb.nodesource.com/setup_5.x | bash -
[sudo] apt-get install -y nodejs
[sudo] npm install lightsword -g

# Using RHEL 6, CentOS 6
[sudo] yum update
[sudo] yum install curl

[sudo] curl -sL https://rpm.nodesource.com/setup_5.x | bash -
[sudo] npm install lightsword -g
```
2.Running 

```
> lsserver --port 8081 --password mypassword --fork --cluster
```

OK, your server is running. To get more information, type: 'lsserver -h' in your terminal.

Now, run Level.4/5 on your iOS/OS X device, tap 'Add Server Configuration', input your server label, address, port number, password, and save it. Switch on the connection toggle, Level.4/5 is going to protect your network traffic.

App Store
---

Level.4 (iOS 9.0 Required)

[<img src="https://devimages.apple.com.edgekey.net/app-store/marketing/guidelines/images/badge-download-on-the-app-store.svg">](https://itunes.apple.com/us/app/level.4/id1082115711?ls=1&mt=8)

Level.5 (OS X 10.11 Required)

[<img src="https://devimages.apple.com.edgekey.net/app-store/marketing/guidelines/mac/images/badge-download-on-the-mac-app-store.svg">](https://itunes.apple.com/us/app/level.5/id1088733081?ls=1&mt=12)

Roadmap:
---

~~1.Debug TCP/IPv4 stack~~ ✓

~~2.Bypass China IP~~ ✓

3.Compatible with SS

4.IPv6

~~5.Today Widget~~ ✓

Privacy Policy
---

Level.4/5 dosen't collect any data about the user.

Progress
---

~~0.1.0 Not Stable (Rejected)~~

~~0.2.0 IMPORTANT UPDATE: Lots of bugs are fixed (Ready for Sale)~~

***0.2.3 IMPORANT UPDATE: Improved performance (Ready for Sale)***

0.3.0 Bypassing China IP (Testing, iOS 9.3 Required)
