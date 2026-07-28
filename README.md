# Linux-password-hashing-and-cracking

## Overview This project demonstrates Linux password storage, password hash identification, and password cracking techniques in a controlled lab environment.  
** Disclaimer: This project was completed in an authorized academic environment for educational purposes only. 

#Skills Demonstrated

- Linux Commandline
- Password hash identification
- Password cracking with Hashcat
- Linux file permissions
- Password security concepts
- File redirection and piping
- Dictionary attacks

## Tools Used

- Kali Linux
- Hashcat
- hash-identifier
- RockYou wordlist
- Bash

## Key Concepts

### Password Storage

- Examined `/etc/passwd`
- Examined `/etc/shadow`
- Compared account information with encrypted password hashes

### Hash Identification

Identified multiple hash algorithms including:

- MD5
- SHA-1
- SHA-256

using **hash-identifier**

### Password Cracking

Used **Hashcat** with the RockYou wordlist to:

- Identify hash types
- Crack MD5 hashes
- Test SHA-1 and SHA-256 hashes
- Analyze successful and unsuccessful cracking attempts

## Security Takeaways

This project reinforced the importance of:

- Strong passwords
- Salted password hashes
- Secure password storage
- Limiting weak dictionary-based passwords

All organizations should avoid weak passwords because they are vulnerable to offline dictionary attacks using publicly available wordlists.

## Screenshots

### Viewing the Linux Password Files

![Shadow File](images/shadow-passwd-comparison(1).png)

![Hash Identifier](images/hash-identifier-md5(1).png)

![Hashcat](images/hashcat-md5-success(1).png)


## What I Learned

This lab strengthened my understanding of how Linux systems store credentials and how attackers can recover weak passwords through offline password cracking. Truly highlighting why modern systems rely on stronger hashing algorithms, and strong password policies to protect user accounts.
