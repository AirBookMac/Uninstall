#!/bin/bash

#Uninstall Script
#Company -=- Creator
#Created on xxx

#This script uninstalls Applications on macOS Client

#Variables
App="$4"
Path="$5"

###################################
### Start uninstall Application ###
###################################

if [[ -d $Path ]]
then
	echo "$App is installed."
	echo "Delete $App."
    rm -rf "$Path"
	if [[ ! -d $Path ]]
	then
		echo "$App has been fully uninstalled."
	else 
		echo "$App is still there."    	
	fi    
else 
echo "$App is not installed."    	
fi

exit 0

#################################
### End uninstall Application ###
#################################
