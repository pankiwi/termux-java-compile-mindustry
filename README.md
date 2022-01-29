# termux-java-compile-mindustry

how install java/kotlin compile termux

```
#necesary
apk in git, wget, unzip, proot, proot-distro, nano

proot-distro install debian

#now login
proot-distro login debian

apt update && apt upgrade
apt install openjdk-17-jdk-headless

#now java --version if not work try it again
apt update && apt upgrade
apt install openjdk-17-jdk-headless

#now try java --version, next

wget https://cdn.discordapp.com/attachments/653293028869537843/927365918588280922/setup-androidsdk-novirus.sh
chmod +x setup-androidsdk-novirus.sh && ./setup-androidsdk-novirus.sh

#now
exit

proot-distro login debian --isolated

#now
nano ~/.bashrc

#remplace end line for it

export PATH=$PATH:$ANDROID_HOME/build-tools/30.0.3

#save changes and exit
crtl s
crtl x

#now compile :D
