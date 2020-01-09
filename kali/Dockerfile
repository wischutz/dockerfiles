# This Dockerfile builds the latest Kali Linux official release, including
# some tools to perform basic pentest's actions

# Last kali official release 
FROM kalilinux/kali

# Update and install the programs of choice
RUN apt-get update && apt-get upgrade -y && apt-get install -y \
apt-utils \
git \
ca-certificates \
sslscan \
host \
hping3 \
net-tools \
netcat \
nikto \
curl \
wfuzz \
wget 



