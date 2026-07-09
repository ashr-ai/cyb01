## Nmap scan report for _gateway (10.10.44.1)
PORT     STATE SERVICE VERSION
22/tcp   open  ssh     OpenSSH 10.0p2 Debian 7+deb13u4 (protocol 2.0)
111/tcp  open  rpcbind 2-4 (RPC #100000)
3128/tcp open  http    Proxmox Virtual Environment REST API 3.0
Service Info: OS: Linux; CPE: cpe:/o:linux:linux_kernel


## Nmap scan report for 10.10.44.9
PORT     STATE SERVICE     VERSION
22/tcp   open  ssh         OpenSSH 9.9 (protocol 2.0)
9090/tcp open  zeus-admin?
1 service unrecognized despite returning data


## Nmap scan report for 10.10.44.20
PORT     STATE  SERVICE    VERSION
22/tcp   open   ssh        OpenSSH 9.6p1 Ubuntu 3ubuntu13.16 (Ubuntu Linux; protocol 2.0)
80/tcp   open   http       nginx 1.24.0 (Ubuntu)
443/tcp  closed https
3306/tcp closed mysql
8080/tcp closed http-proxy
Service Info: OS: Linux; CPE: cpe:/o:linux:linux_kernel


## réseau complet
Nmap scan report for _gateway (10.10.44.1)
Host is up (0.00078s latency).
Not shown: 997 closed tcp ports (conn-refused)
PORT     STATE SERVICE VERSION
22/tcp   open  ssh     OpenSSH 10.0p2 Debian 7+deb13u4 (protocol 2.0)
111/tcp  open  rpcbind 2-4 (RPC #100000)
3128/tcp open  http    Proxmox Virtual Environment REST API 3.0
Service Info: OS: Linux; CPE: cpe:/o:linux:linux_kernel

Nmap scan report for aj-Standard-PC-i440FX-PIIX-1996 (10.10.44.2)
Host is up (0.00018s latency).
Not shown: 998 closed tcp ports (conn-refused)
PORT     STATE SERVICE       VERSION
22/tcp   open  ssh           OpenSSH 9.6p1 Ubuntu 3ubuntu13.16 (Ubuntu Linux; protocol 2.0)
3389/tcp open  ms-wbt-server Microsoft Terminal Service
Service Info: OSs: Linux, Windows; CPE: cpe:/o:linux:linux_kernel, cpe:/o:microsoft:windows

Nmap scan report for 10.10.44.20
Host is up (0.00052s latency).
Not shown: 995 filtered tcp ports (no-response)
PORT     STATE  SERVICE    VERSION
22/tcp   open   ssh        OpenSSH 9.6p1 Ubuntu 3ubuntu13.16 (Ubuntu Linux; protocol 2.0)
80/tcp   open   http       nginx 1.24.0 (Ubuntu)
443/tcp  closed https
3306/tcp closed mysql
8080/tcp closed http-proxy
Service Info: OS: Linux; CPE: cpe:/o:linux:linux_kernel

Nmap scan report for 10.10.44.99
Host is up (0.00085s latency).
Not shown: 999 closed tcp ports (conn-refused)
PORT   STATE SERVICE VERSION
22/tcp open  ssh     OpenSSH 9.6p1 Ubuntu 3ubuntu13.16 (Ubuntu Linux; protocol 2.0)
Service Info: OS: Linux; CPE: cpe:/o:linux:linux_kernel

Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .
Nmap done: 256 IP addresses (4 hosts up) scanned in 18.60 seconds
