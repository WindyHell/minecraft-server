# minecraft-server

### Code: #
 - OS Creating:
    + sudo apt update
    + sudo apt upgrade
 - Core (Paper 1.18.2):
    + wget https://api.papermc.io/v2/projects/paper/versions/1.18.2/builds/388/downloads/paper-1.18.2-388.jar
 - Run:
    + java -Xmx12288M -Xms12288M -jar paper-1.18.2-388.jar nogui
### Port Forwarding: #
 - Install:
    + wget -O ngrok.tgz "https://bin.equinox.io/c/bNyj1mQVY4c/ngrok-v3-stable-linux-amd64.tgz"
    + tar -xf ngrok.tgz
 - Add Token:
    + ./ngrok authtoken 'insert authtoken here'
 - Open Port: 
    + ./ngrok tcp <port>

### Console: #
 - Install:
    + sudo apt install glances
 - Use:
    + glances
