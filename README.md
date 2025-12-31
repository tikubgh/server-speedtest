VPS server speedtest checker

## 🚀 Installation: Speedtest - Debian 13

- sudo apt-get install curl && curl -s https://packagecloud.io/install/repositories/ookla/speedtest-cli/script.deb.sh | sudo bash
- sudo apt-get install speedtest
- speedtest
- speedtest --accept-license --accept-gdpr


Alternative loop
- sudo apt update && sudo apt install speedtest-cli
- while true; do speedtest; sleep 5; done


## 🚀 Installation: Fast - Debian 13

- curl -sSL https://raw.githubusercontent.com/mikkelam/fast-cli/main/install.sh | bash
- fast-cli --upload
