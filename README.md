   > pkg update && pkg upgrade
   > pkg install proot-distro
   > proot-distro install alpine
   > proot-distro login alpine
   > apk update && apk add --no-cache nmap && \
  echo @edge http://nl.alpinelinux.org/alpine/edge/community >> /etc/apk/repositories && \
  echo @edge http://nl.alpinelinux.org/alpine/edge/main >> /etc/apk/repositories && \
  apk update && \
  apk add --no-cache \
  chromium
   > apk add --update nodejs npm git
   > git clone https://github.com/Alsarmad/whatsapp_adhkar
   > cd whatsapp_adhkar
   > npm i
   > npm start
