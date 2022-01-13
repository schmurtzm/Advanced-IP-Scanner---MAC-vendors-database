# Advanced-IP-Scanner - MAC-vendors-database
---

This is an update of the mac address vendors database for [Advanced IP Scanner](https://www.advanced-ip-scanner.com/).

Just replace the file mac_interval_tree.txt in your "C:\Program Files (x86)\Advanced IP Scanner" folder and restart Advanced IP Scanner.

----------

[Here an updated database](https://maclookup.app/downloads/csv-database) which has been used for the update.

Useful Google Spreadsheet formula to arrange the mac address list in the right format for Advanced-IP-Scanner :

```=SUBSTITUTE(A2; ":"; "")&REPT("F";14-LEN(A2))```

----------

[Related post on Advanced-IP-Scanner's forum](https://radmin-club.com/advanced-ip-scanner/bug-with-cache-when-using-portable-mode1/)

Do not hesitate to fork an participate to the update with pull request ;)
