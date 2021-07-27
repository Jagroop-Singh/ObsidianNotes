# Hashcat
Usage: hashcat \[options] hash|hashfile|hccapxfile \[dictionary|mask|directory]
Requires 4 Arguments minimum
- ``-m`` (or ``--hash-type``)
	- For Example, MD5, SHA1, etc.
	- Full list of hash types can be found by using "--help"
	- Currently supports 237 different hash types
	- `-m 0` for MD5 hash
- `-a` (or `--attack-mode`)
	- Tells Hashcat how to crack the passwords
	- For example, using a dictionary of words, or brute-force
	- ``-a 0`` specifies a dictionary attack
- \[filename | hash]
	- Specifies a file containing the hash(es) you intend to crack
- \[dictionary | mask | directory]
	- Specifies a dictionary (wordlist), mask, or directory intended to be used
	- One of the most popular is the rockyou.txt wordlist