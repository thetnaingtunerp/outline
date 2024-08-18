# outline

[12700:0818/144933.575039:FATAL:setuid_sandbox_host.cc(157)] The SUID sandbox helper binary was found, but is not configured correctly. Rather than run without sandboxing I'm aborting now. You need to make sure that /tmp/.mount_OutlinQhvb0N/chrome-sandbox is owned by root and has mode 4755.
Trace/breakpoint trap (core dumped)


sudo chown root:root /tmp/.mount_OutlinQhvb0N/chrome-sandbox
sudo chmod 4755 /tmp/.mount_OutlinQhvb0N/chrome-sandbox

chown: cannot access '/tmp/.mount_OutlinQhvb0N/chrome-sandbox': No such file or directory
chown: cannot access 'sudo': No such file or directory
chown: cannot access 'chmod': No such file or directory
chown: cannot access '4755': No such file or directory
chown: cannot access '/tmp/.mount_OutlinQhvb0N/chrome-sandbox': No such file or directory
bluestar@kot
