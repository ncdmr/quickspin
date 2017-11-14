# vagrant-quickspin

A Vagrant configuration to spin up X number of machines with dynamic hostnames,ips & portnumbers.

## Prerequisites

Vagrant and something like VirtualBox.

## Getting Started

Clone the repo in a folder, adjust according to your needs and spin up using 
```
-> % vagrant up
[...]
-> % vagrant status
Current machine states:

server1                   running (virtualbox)
server2                   running (virtualbox)
server3                   running (virtualbox)
server4                   running (virtualbox)
server5                   running (virtualbox)
server6                   running (virtualbox)
```

Note: add ```vb.gui=true``` in case you need to see the terminals.