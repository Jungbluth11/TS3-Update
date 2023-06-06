# TS3-Update
With this little script you can easily update your TS3 server automatically.
Works with Exagear on Raspberry Pi.

# Requirements
Server running a linux x86 TS3 Server
Server Directory Named "teamspeak3-server_linux_x86"
Run the script in the directory where the server's directory is located.

for example:

    /home/ts3/teamspeak3-server_linux_x86/{TS3 server files}
    /home/ts3/ts3update.sh (This Script)

# Install 

    wget the link of version
    chmod +x ts3update.sh
    ./ts3update.sh

Run:

    wget -Nnv https://github.com/Jungbluth11/TS3-Update/releases/download/1.0.1/ts3update.sh && chmod +x ts3update.sh; ./ts3update.sh

Add a crontab that will start the script regularly.
