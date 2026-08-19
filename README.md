# TryHackMe Writeups

Personal log of TryHackMe rooms completed, written up as methodology notes rather than
flag dumps. Built while working toward eJPT / Security+ and a move into penetration
testing.

> Only writeups for **free/community rooms** are published here, in line with
> TryHackMe's terms. Premium room content stays private.

## Index

| Room | Category | Key Skills | Difficulty | Writeup |
|---|---|---|---|---|
| _(add as completed)_ | | | | |

## Structure

```
writeups/
  linux-fundamentals/
  web-exploitation/
  privilege-escalation/
  network-security/
  digital-forensics/
  active-directory/
  ctf-collections/
resources/
  cheatsheets/      # command references, payload lists, quick lookups
  tool-notes/        # notes on nmap, burp, metasploit, etc.
scripts/              # small helper scripts (recon automation, parsers)
```

## Writeup format

Each writeup follows the same shape (see `writeups/_TEMPLATE.md`):
1. **Recon** — what was found and how
2. **Foothold** — the vulnerability and how it was exploited
3. **Privilege escalation** — path to root/system
4. **Lessons** — what this room taught, and how it maps to real-world TTPs

The goal is to demonstrate methodology, not just "flag: xyz" — that's what a
reviewer skimming this for a CV actually cares about.
