---
permalink: /about/
title: "About"
excerpt: "Penetration tester focused on web, API, and Android security — and on building the tooling to do it faster."
---

I'm **Mahmoud Ahmed**, a penetration tester based in Egypt. I spend most of my time finding
security flaws in production web applications, APIs, and Android apps — then writing them up
so they actually get fixed. I care about reproducing real impact, not flagging a symptom.

## How I got here

My work started, and still largely lives, in bug bounty. Through independent research on
HackerOne and other platforms I've reported and disclosed vulnerabilities across access-control
and configuration weaknesses — **CORS misconfigurations** (arbitrary-origin reflection and
null-origin via sandboxed iframes), **SSRF chains**, **publicly misconfigured S3 buckets**,
**excessive data exposure**, and exposed services leaking internal DNS and infrastructure
details. Every submission ships with a reproducible proof-of-concept and a severity rating
grounded in verified impact. I'd rather report one solid finding than ten speculative ones.

I also audit source code. A review of a **Lightning Network SDK and UI library** turned up
critical issues — payment preimage exposure in GraphQL responses and private-key
over-fetching — which I developed into a full proof-of-concept for an **HTLC griefing attack**.
On the application side I do static APK analysis, ADB-driven dynamic fuzzing, and Frida
instrumentation. I gained structured, team-based practice during a web application penetration
testing internship at **Penforce**, working through the OWASP Top 10 with industry tooling and
taking part in simulated incident-response exercises.

Alongside testing, I build the tools I wish existed. That includes MCP-based agents for web/API
and Android testing (out-of-band callbacks, multi-user session handling for access-control
checks, state chaining, per-host rate limiting) and an AI-agent detection honeypot. LLM and
agentic security is the area I'm most excited about.

## What I work on

- **Web & API security** — manual testing, OWASP Top 10, authentication and multi-user
  access-control testing, CORS / SSRF / data-exposure classes.
- **Mobile security** — Android static and dynamic analysis (jadx, ADB, Frida).
- **Source code review & malware analysis** — static/dynamic analysis and reverse
  engineering with Ghidra.
- **Security tooling & AI** — custom MCP-based testing infrastructure and LLM/agentic security.

## Tooling

Burp Suite · Nmap · Metasploit · Nessus · Acunetix · Wireshark · Ghidra · Frida · ADB
— plus Python, JavaScript (Node.js), Bash, PHP, and SQL for custom tooling.

## Background

Studying Computer Science at **Tanta University** (Faculty of Computers and Information), with a
Red Team Diploma and Malware Analysis training, and mentorship through **CAT Reloaded MU**.
CTF participant. Certified across red-team operations, cybersecurity education, and LLM security.

## Elsewhere

- GitHub — [github.com/0-AM-X](https://github.com/0-AM-X)
- LinkedIn — [mahmoud-yahia](https://www.linkedin.com/in/mahmoud-yahia-7a5514293/)
- Email — [n.k.t.g049@gmail.com](mailto:n.k.t.g049@gmail.com)

Interested in security, tooling, or collaborating on something? Get in touch.
