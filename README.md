# notes-for-debugging

DISPLAY LISTENING PORTS
The command sudo netstat -ltnp is used to display listening ports along with the processes that are bound to them on Linux. This can help you identify which process is using a specific port. Here's a breakdown of the command:

sudo: Run the command with superuser privileges.
netstat: Display network-related information, including listening ports.
-l: Show only listening sockets.
-t: Display TCP connections.
-n: Display numerical addresses instead of resolving them.
-p: Show the process ID and name of the program.
