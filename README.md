# AdGuardHome
- termux setup
- pkg install openssh
- passwd
- whoami
- ip a
- ssh u0_a138@192.168.1.64 -p 8022
- pkg update && pkg upgrade
- termux-setup-storage
- termux-wake-lock

curl -L -o AdGuardHome.tar.gz https://github.com/AdguardTeam/AdGuardHome/releases/download/v0.107.43/AdGuardHome_linux_arm64.tar.gz
tar -xvzf AdGuardHome.tar.gz
cd AdGuardHome
chmod +x AdGuardHome
su
./AdGuardHome &
