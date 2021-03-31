# IoT Vulns Record

## Timeline

- 2020/4/30~2020/5/3. 11 vulnerabilities of **DrayTek Vigor 2960/3900/300B VPN Router** were found by us(C0ss4ck, Swing, MozhuCY), 3 of them are unauthorized. All of them have been reported to DrayTek and MITRE
	- CVE-2020-14472
	- CVE-2020-14473
- 2020/5/25. 1 vulnerability of **D-Link DSR VPN Router** was found by me(C0ss4ck), which locates @ upnpd. It has been reported to 补天, consequently its detail is secret.
- 2020/8/3. 1 vulnerability of **MARLBOZE** was found by us(H4lo, C0ss4ck), which locates @ p2pcam. *ALL DETAIL IS SECRET*.
	- Thanks to WMCTF's challenge 'ipcam'
- 2020/9/02. Multiple vulnerabilities of **HICHIP** were found by us(C0ss4ck, H4lo, MozhuCY). *ALL DETAIL IS SECRET*.
	- Maybe some months or years later, we'll publish(or sell) a tool to exploit HICHIP.
- 2020/11/03, 1 vulnerablity of **ZTE Topbox** was found by me(C0ss4ck), which caused by unsafe SSI. *ALL DETAIL IS SECRET*.
- 2020/12/22, 2 backdoors of **ZTE Topbox** were found by us(C0ss4ck, MozhuCY). *ALL DETAIL IS SECRET*.
- 2021/2/1, an funny vulnerability of  **DrayTek Vigor 2960/3900/300B VPN Router** was found by us(C0ss4ck, H4lo), which has no need of authorization. Finnaly it was reported to DrayTek and CNVD
	- CNVD-2021-17368


## Summary

As we prepared, we are going to 
1. develop a tool to scan CMDi inside any binary.
2. research on mail server.
3. target on mobile OS.