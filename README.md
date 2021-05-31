# CTF

This repository will serve as a central resource for me to be able to collect, modify, add, delete, and create scripts that were used during participation in Capture-The-Flag events.

cat ip_list | grep -E -o "/bot/([0-9]{1,3}[.]){3}[0-9]{1,3}" | grep -E -o "([0-9]{1,3}[.]){3}[0-9]{1,3}"| sort -n | uniq -c | sort -n | grep -E -o "([0-9]{1,3}[.]){3}[0-9]{1,3}" | tee ip_target
