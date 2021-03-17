# uceprotect-check

- netmask.sh = Convert Block IP to Single IP / List IP Address from that block and save to `list-ip.txt`
- rbl_check_only = Check blacklist uceprotect from IP on `list-ip.txt` and save the result into `result.txt`
- rbl_check = Execute `netmask.sh` and `rbl_check_only` also sent notification when IP address has been found on uceprotect List
