# CVE-2024-10914  D-Link Remote Code Execution (RCE)
<img src=https://github.com/redspy-sec/D-Link/blob/e20a3a8ef405183b9d4d3b5b4225fb8c2cff3fd1/Screenshot_20241207-002840.jpg/>

# D-Link NAS- Command Injection via Name Parameter CVE-2024-10914:- 
A vulnerability was found in D-Link DNS-320, DNS- 320LW, DNS-325 and DNS-340L up to 20241028. It has been declared as critical. Affected by this vulnerability is the function cgi_user_add of the file /cgi-bin/account_mgr.cgi?cmd=cgi_user_ado. The manipulation off the argument name leads to os command injection. 

Dork FOFA: app="D_Link-DNS-ShareCenter"
