#!/bin/bash
# My first script

i=$(ip addr | grep 'eth0' | tail -n1 | awk '{print $2}' | cut -f1 -d'/')
d=$(pwd)
echo "ssh://"$USER"@"$i$d

