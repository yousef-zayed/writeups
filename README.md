# TryHackMe Writeups
 
A collection of writeups documenting my progress through TryHackMe's Jr Penetration Tester path and related CTF rooms. Each writeup covers reconnaissance, exploitation, and privilege escalation, with supporting evidence (screenshots, command output) alongside the analysis.
 
## About
 
I'm a CS student building practical offensive security skills, working through TryHackMe rooms as part of self-directed study toward a penetration testing career path. These writeups aim to show full methodology — not just "what worked," but the reasoning behind each step, dead ends investigated, and lessons learned along the way.
 
## Structure
 
Each room has its own directory containing a `README.md` writeup and an `evidence/` folder with supporting screenshots:
 
```
room-name/
├── README.md       # Full writeup
└── evidence/       # All command outputs and screenshots used throughout the CTF
    ├── command_outputs/
    └── screenshots/
```
 
## Writeups
 
| Room | Difficulty | Key Topics | Link |
|------|-----------|------------|------|
| Simple CTF | Easy | FTP enum, Hydra brute-force, CMS Made Simple SQLi (CVE-2019-9053), sudo vim privesc | [Writeup](./simple_ctf/) |
| Recruit | Medium | Web, SSRF, SQLi | [Writeup](./recruit/) |
| Support | Medium | Web exploitation, LFI/file disclosure, authentication, brute-force, RCE| [Writeup](./support/) |
 
*(Table updated as new writeups are added.)*
 
## Tools Commonly Used
 
- **Recon:** `nmap`, `gobuster`, `nikto`
- **Web:** Burp Suite, `curl`, browser dev tools
- **Brute-force:** `hydra`
- **Cracking:** `john`, `hashcat`
- **Exploitation:** `searchsploit`, manual PoC adaptation, Metasploit (where applicable)
## Disclaimer
 
All activity documented here was performed against intentionally vulnerable machines on TryHackMe, in accordance with their terms of service. Nothing in this repository targets systems without authorization.