#  TCP Flood

I recommend installing Wireshark in order to see how the normal traffic changes.
I have used this for educational usage, and flooded my own home computer and should only send 100 packages.

The script takes in two argument, so in order to make it work insert a target IP address and Port.

##### OBS
You might want to change "and_ips=[("192.168.1."+str(random.randint(0,255))) for _ in range(10)]" to your own subnet to make it work.

## Beaware 
It might be illegal to send the traffic to any computer, so only use it on your private network or networks where you have a clear permission to do so. I personally used VmWare to test the script on my own homenetwork and work pc.
