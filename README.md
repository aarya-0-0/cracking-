Home Lab Practice: Capturing NetNTLMv2 hashes with Responder and cracking them using Hashcat (mode 5600).

OBJECTIVE: To crack the password in the form of NetNTLMv2 has

TOOLS USED: 
- Responder
- Hashcat
- Windows server 2012
- Kali Linux

PROCEDURE:
- In Kali linux, fire the command to let the responder come into action.
- In the run command of Windows 2012 server, run a fake login page.
- Enter the credentials.
- Capture the NetNTLMv2 hash from the responder
- Fire the hashcat command using mode 5600 and with rockyou.txt wordlist under /usr/share directory of kali linux.
  (I have used -o option with file name 'crack' to store the cracked password into it)

WHAT I LEARNED 
- Different type of hashes like NTLM, NTLM raw, NTLMv1, NTLMv2
- To read the result of hashcat
- To listen the local communication using Responder

(view the attached screenshots of my project)

