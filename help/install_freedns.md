1. `sudo contab -e`
2. Add something like this (replace `ADD_YOUR_ID` with your key)
    0 3 * * * wget --no-check-certificate -O - https://freedns.afraid.org/dynamic/update.php?ADD_YOUR_ID >> /dev/null 2>&1
