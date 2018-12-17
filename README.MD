# This is an easy fix for the UTC problem when working with dualboot

open Terminal (CRTL+ALT+T)
type `timedatectl set-local-rtc 1 --adjust-system-clock`
enter
type `timedatectl`


or just run script.sh


This solution is from [here](http://ubuntuhandbook.org/index.php/2016/05/time-differences-ubuntu-1604-windows-10/)

this was implemented by Simon Schuler