#! /bin/bash
#
for i in $(cat /etc/passwd  | cut -d: -f1); do
   echo -n $i ": "
   grep $i /etc/group | cut -d: -f1 | tr "\n" " "
   echo
done
