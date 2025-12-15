# Super SSH

**Category:** General Skills  
**Difficulty:** Easy  
**Status:** Practice  

---

## Problem Overview
The challenge provides a username, server address, and port number, and asks us to connect to a remote server to retrieve the flag.

---

## Key Concept
SSH (Secure Shell) is a protocol used to securely connect to a remote server and access its terminal. It allows users to run commands on another machine over an encrypted connection.

---

## Solution Walkthrough
1. The challenge provides the required SSH credentials:
   - Username
   - Server address
   - Port number

2. I used the following command to connect to the server:

```bash
ssh username@server -p portNumber
```
3. On the first connection, the server asked to confirm its fingerprint. I accepted it by typing yes.

4. After entering the correct password, I successfully logged into the remote server and gained access to its terminal.

5. The flag was available on the server and was displayed after logging in.

## Flag
picoCTF{REDACTED}
