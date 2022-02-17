# Contruindo-Firmware-Android

-------------
Instale jdk no PC <br>

sudo apt-get install software-properties-common <br>
sudo add-apt-repository ppa:webupd8team/java <br>
sudo apt-get update <br>
sudo apt-get install oracle-java6-installer <br>

-------------
Instalar pacotes essenciais <br>

sudo apt-get install git gnupg flex bison gperf build-essential \ <br>
 zip curl libc6-dev libncurses5-dev:i386 x11proto-core-dev \ <br>
 libx11-dev:i386 libreadline-dev:i386 libgl1-mesa-glx:i386 \ <br>
 libgl1-mesa-dev g++-multilib mingw-w64 tofrodos \ <br>
 python-markdown libxml2-utils xsltproc zlib1g-dev:i386 <br>

-------------
Vincule a biblioteca libGL: <br>
sudo ln -s /usr/lib/i386-linux-gnu/mesa/libGL.so.1 /usr/lib/i386-linux-gnu/libGL.so

-------------
Install SDK <br>

sudo apt update && sudo apt install android-sdk <br>
A localização do Android SDK no Linux pode ser qualquer uma das seguintes: <br>

/home/AccountName/Android/Sdk <br>

/usr/lib/android-sdk <br>

/Library/Android/sdk/ <br>

/Users/[USER]/Library/Android/sdk <br>
