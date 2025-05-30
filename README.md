In this, the goal was to configure and test basic firewall rules using Windows Defender Firewall on my local machine. I opened the advanced firewall settings and created a custom inbound rule to block port 23, which is used by Telnet (an old and insecure protocol).

After applying the rule, I tested it by running the command telnet localhost 23 in the Command Prompt, which failed to connect—proving the firewall was successfully blocking traffic on that port.

I then removed the rule to restore normal system behavior. Through this, I learned how firewall rules work by inspecting traffic at the port level and either allowing or denying it based on defined rules. This is one of the simplest yet most important ways to harden a system against attacks.
