# AdGuardHome Termux Setup + Root Android
- pkg install openssh
- passwd
- whoami
- ip a
- ssh u0_aXXX@192.168.X.X -p 8022
- pkg update && pkg upgrade
- pkg install termux-api
- termux-setup-storage (không dùng cũng được)
- termux-wake-lock

- curl -L -o AdGuardHome.tar.gz https://github.com/AdguardTeam/AdGuardHome/releases/download/v0.107.43/AdGuardHome_linux_arm64.tar.gz
- tar -xvzf AdGuardHome.tar.gz
- rm -rf ./AdGuardHome.tar.gz
- cd AdGuardHome
- chmod +x AdGuardHome
- su
- ./AdGuardHome &

- lưu ý trỏ dns về ip đt cả wifi và thiết bị kết nói wifi 
