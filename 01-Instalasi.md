# Instalasi Oracle JDK v13

## I. Instalasi Oracle JDK v13 pada sistem operasi Linux berbasis Debian

Buka Terminal dan ketik perintah berikut,

1. `sudo apt install dirmngr gnupg`
2. `sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv-keys 73C3DB2A`
3. `echo 'deb http://ppa.launchpad.net/linuxuprising/java/ubuntu bionic main' | sudo tee /etc/apt/sources.list.d/linuxuprising-java.list`
4. `sudo apt update`
5. `sudo apt install oracle-java13-installer`
6. Set default Java ke Oracle JDK v13: `sudo apt install oracle-java13-set-default`
7. Cek versi Java untuk memastikan Java terinstall dengan baik: `java -version`
