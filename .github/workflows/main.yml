#!/bin/bash
_mydir="`pwd`"
filename=chinnu.txt
if find $_mydir -name $filename|grep '^'; then
# Take the fruit name from the file
read -p "Enter the fruit name from file : " search
# take the new input fruit name to replace in file
read -p "Enter the new fruit name : " replace
# will make changes of content in orginal file
if [[ $search != "" && $replace != "" ]]; then
sed -i "s/$search/$replace/" $filename
fi
else
  echo "the file does not exist!"
fi
