# CamShot
Grab cam shots from target's phone front camera or PC webcam just sending a link

# What is CamShot?
<p>CamPhish is techniques to take cam shots of target's phone front camera or PC webcam. CamShot Hosts a fake website on in built PHP server and uses ngrok & serveo to generate a link which we will forward to the target, which can be used on over internet. website asks for camera permission and if the target allows it, this tool grab camshots of target's device</p>

## Features
<p>In this tool I added two automatic webpage templates for engaged target on webpage to get more picture of cam</p>
<ul>
  <li>Festival Wishing</li>
  <li>Live YouTube TV</li>
   <li>Online Meeting [Beta]</li>
</ul>
<p>simply enter festival name or youtube's video ID</p>

## This Tool Tested On :
<ul>
  <li>Kali Linux</li>
  <li>Termux</li>
  <li>MacOS</li>
  <li>Ubuntu</li>
  <li>Parrot Sec OS</li>
</ul>

# Installing and requirements
<p>This tool require PHP for webserver, SSH or serveo link. First run following command on your terminal</p>

```
apt-get -y install php openssh git wget
```

## Installing (Kali Linux/Termux):

```
git clone https://github.com/Ali56Arif/CamShot
cd CamShot
bash camshot.sh
```

## Change Log:

<p><b>Version: 1.5:</b> Add new online meeting template</p>
<p><b>Version: 1.4:</b> Ngrok authtoken update</p>
<p><b>Version: 1.3:</b> Fix ngrok direct link</p>

### Camshot
![image](https://user-images.githubusercontent.com/79138028/216158972-35c44302-08d3-4989-9dbd-0e0c38cc2c87.png)

#### For More Video subcribe <a href="http://youtube.com/caarifmediatech">Caarif Media Tech</a>
<p>CamShot is created to help in penetration testing and it's not responsible for any misuse or illegal purposes.</p>
<p>CamShot is inspired by https://github.com/thelinuxchoice/ Big thanks to @thelinuxchoice</p>
