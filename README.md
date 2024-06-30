# nginx-minecraft-proxy
 Routes a connection from a client to the upstream Minecraft server.
# Use
(instructions for Ubuntu)
1. Download `mc.conf` file.
2. Place file in `/etc/nginx/modules-available`.
3. Run `sudo ln -s /etc/nginx/modules-available/mc.conf /etc/nginx/modules-enabled/mc.conf`.
