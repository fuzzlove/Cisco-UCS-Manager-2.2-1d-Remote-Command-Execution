# Cisco-UCS-Manager-2.2-1d-Remote-Command-Execution - CVE-2015-6435


Exploit Title         : Cisco UCS Manager - 2.2(1d) - Remote Command Execution
Description           : An unspecified CGI script in Cisco FX-OS before 1.1.2 on Firepower 9000 devices and Cisco Unified Computing System (UCS) Manager before 2.2(4b), 2.2(5) before 2.2(5a), and 3.0 before 3.0(2e) allows remote attackers to execute arbitrary shell commands via a crafted HTTP request, aka Bug ID CSCur90888.
Date                  : 1/15/2021
Exploit Author        : liquidsky (J.McPeters)
Vulnerable Software   : Cisco UCS Manager - 2.2(1d) -> [According to the vendor (cisco), this is known to impact versions prior to 3.0(2e).]
Vendor Homepage       : https://www.cisco.com/c/en/us/products/servers-unified-computing/ucs-manager/index.html
Version               : 2.2(1d), 2.2(3c)A
Cisco Reference       : https://quickview.cloudapps.cisco.com/quickview/bug/CSCur90888
Tested On             : Cisco UCS Manager - 2.2(1d) (Exploit ran with Debian 5.6.7-1kali1 (Kali 2020.1 x64))
Author Site           : https://github.com/fuzzlove/Cisco-UCS-Manager-2.2-1d-Remote-Command-Execution
Demo                  : https://youtu.be/bZAcJrwPEb0
CVE                   : CVE-2015-6435 | https://nvd.nist.gov/vuln/detail/CVE-2015-6435
Special Notes         : This application by default uses outdated TLS 1.0 for communication, so thats why there is a quickfix/temporary patch to 1.0 in openssl utilizing 'sed' (that gets changes back after exploitation).

Greetz: wetw0rk, Fr13ndz, O.G.Xx25, MS, SS, JK, the S3 family, and last but NOT least droppunx ^_~
