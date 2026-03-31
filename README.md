# Hashcat Password Cracking Demo

This project demonstrates password cracking using Hashcat.

## Steps:
1. Generate hash from password
2. Store hash in hash.txt
3. Create wordlist.txt
4. Run command:

hashcat -m 0 -a 0 hash.txt wordlist.txt

## Output:
Hashcat compares hashes and recovers the original password.

## Tool Used:
Hashcat
