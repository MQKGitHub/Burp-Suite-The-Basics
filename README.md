### 🛡️ Burp Suite: The Basics

**Room:** [Burp Suite: The Basics — TryHackMe](https://tryhackme.com/room/burpsuitebasics)  
**Status:** ✅ Completed  
**Date:** *05 June 2025* 

### 🎯 Objective
Gain a solid introduction to Burp Suite, its interface, and tools. Understand how to install and configure Burp Suite, use the Burp Proxy, and perform basic web application testing including intercepting and manipulating HTTP requests.

---

### 🗝️ Key Concepts  
- **Burp Suite** — A Java-based toolkit for web app penetration testing that captures and manipulates HTTP/HTTPS traffic.
- **Burp Proxy** — Intercepts and logs web requests/responses; lets you modify traffic before forwarding it.
- **Repeater** — Used to modify and resend the same request multiple times.
- **Intruder** — Used for brute-force and fuzzing attacks, though limited in the Community Edition.
- **Decoder** — Encodes and decodes data (e.g. base64, URL-encoding).
- **Comparer** — Compares two data sets (e.g. before/after a request).
- **Sequencer** — Assesses randomness of session tokens.
- **Scope** — Defines what targets are included in the testing; helps limit traffic to relevant endpoints.
- **FoxyProxy** — A browser extension that routes traffic through a proxy like Burp Suite.
- **Reflected XSS** — A type of XSS attack where a malicious script is reflected off a web server and executed immediately.

---

### 🛠️ Tools Used
- **Burp Suite Community Edition** — Used for intercepting and manipulating web traffic.
- **FoxyProxy (Firefox)** — Used to route browser traffic through Burp Proxy.
- **Burp's Built-in Chromium Browser** — Pre-configured browser that automatically works with Burp Proxy.
- **URL Encoding** — Encoded an XSS payload to bypass client-side filters.

---

### ⚠️ Challenges Faced
- The interface felt a bit overwhelming at first with all the quadrants and tabs.
- Took a bit of time to properly set up proxy settings using FoxyProxy and test that it was intercepting correctly.
- Needed to understand the difference between global and project settings — especially since Burp Community doesn’t save sessions.

---

### 🧠 What I Learned
- How to launch and configure Burp Suite for basic usage.
- How to intercept, edit, and forward HTTP requests using the Proxy.
- How to encode payloads (like XSS scripts) within intercepted requests.
- Navigated key modules like Repeater, Intruder, and Target Site Map.
- Scoped traffic to stay focused on a single web app and avoid clutter.

---

### 🌐 Real-World Application:
> Burp Suite is used by ethical hackers, bug bounty hunters, and penetration testers to find vulnerabilities in websites and APIs. For example, intercepting login forms to test for SQL injection, or capturing session cookies to analyse authentication flows. Tools like Repeater and Proxy are central to manual testing workflows.

---

### 💭 Reflections:
- This was a really practical and important room. Seeing an actual XSS attack play out made the theory click.
- I like that Burp has so many tools all in one place. It feels like a control panel for attacking web apps.
- I’m excited to get into the Repeater and more advanced usage in the next rooms. I feel more confident with intercepting now. 
