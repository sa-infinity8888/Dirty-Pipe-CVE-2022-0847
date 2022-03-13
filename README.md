# Dirty-Pipe-CVE-2022-0847

CVE-2022-0847 (Dirty Pipe) is an arbitrary file overwrite vulnerability that allows escalation of privileges by modifying or overwriting arbitrary read-only files e.g. /etc/passwd, /etc/shadow.

# Steps

1. Compile using `gcc cve-2022-0847-exploit.c -o cve-2022-0847-exploit`
2. Run the exploit `./cve-2022-0847-exploit`

# Disclaimer
I do not claim any credit for the discovery of this vulnerability or the code. 
<br/>Check out the official disclosure here: https://dirtypipe.cm4all.com/
