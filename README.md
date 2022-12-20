# SSHPLUS

apt update -y && apt upgrade -y && wget https://raw.githubusercontent.com/tblesshack/SSHPlus/master/Plus && chmod 777 Plus && ./Plus


#Acessa Root

wget https://raw.githubusercontent.com/tblesshack/SSHPlus/master/senharoot.sh && chmod 777 senharoot.sh && ./senharoot.sh

Install BadVPN on ARM

wget https://raw.githubusercontent.com/tblesshack/SSHPlus/master/badvpn-udpgw-arm.zip

unzip badvpn-udpgw-arm.zip

mv -f $HOME/arm/badvpn-udpgw /bin/badvpn-udpgw

chmod 777 /bin/badvpn-udpgw
