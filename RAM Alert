#!/bin/bash
TO="9566569265a@gmail.com","princevermadevops@gmail.com"
ram_free=$(free -mt | grep Total:|awk '{print $4}')

if [ $ram_free -le 6000 ]
then
   echo "sending mail because your free size is is less than 6000"
   echo "Subject:warning,RAM free size is low"|sendmail $TO
fi
