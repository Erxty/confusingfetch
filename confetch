#!/bin/sh

uptime=$(cut -d' ' -f1 /proc/uptime | cut -d'.' -f1)
uptime_minutes=$(( $uptime / 60 ))

echo $USER'@'$HOSTNAME

echo "    .--."
echo "   |o_o |"
echo "   |:_/ |"
echo "  //   \\ \\"
echo " (j     l )"
echo "/'\_   _/'\\"
echo "\___)=(___/"

echo '
shitty os btw'
grep "^NAME=" /etc/os-release
echo ''

echo 'also the colonel sanders?'
uname -r

if [ $uptime -gt 100000 ]; then
	echo "ew get off your computer wtf. Youve been on for ${uptime_minutes} min"
elif [ $uptime -gt 50000 ]; then
	echo "go touch some grass, ok? ${uptime_minutes} min"
elif [ $uptime -gt 10000 ]; then
	echo "keep on using that computer, computer boy. ${uptime_minutes} min"
elif [ $uptime -gt 1000 ]; then
	echo "wow, not too much, huh? ${uptime_minutes} min"
else 
	echo "computah, make this guy super gay, horny, 
	  and addicted to their pc. ${uptime_minutes} min"
fi

echo '
package amount or atleast close enough'
ls -1 /bin/ | wc -l

echo '
sudo apt ddos' $USER

echo '
some random sea'$SHELL' found on the deepweb'

echo ''

if [ $TERM = foot ]; then
	echo 'ew you like feet? wtf. term = ew im not saying that'
elif [ $TERM = kitty ]; then
	echo 'oh i love cats too! term = cat'
elif [ $TERM = urxvt ]; then
	echo 'the best x11 term btw. term = ' $TERM
else
	echo 'term =' $TERM
fi

echo '
well specs. I suppose ik what that is'

echo "cpu=$(uname -p)"

echo "ram=$(grep MemTotal /proc/meminfo | tr -s ' ' | cut -d' ' -f2) KB"

echo "gpu=you dont have one you poor bastard"
