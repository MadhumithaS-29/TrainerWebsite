# Cybersecurity Training Portal

An interactive, browser-based cybersecurity training platform built with standalone HTML, CSS, and JavaScript. The portal introduces core networking and web-security concepts through guided modules, practical command references, vulnerability explanations, and learner progress tracking.

## Features

- **Interactive training modules** covering:
  - Networking basics
  - Nmap
  - Zenmap
  - Wireshark
  - Linux essentials
  - Web vulnerabilities
  - Quick reference material
- **Searchable learning content** for quickly finding topics, commands, filters, and vulnerability concepts.
- **Copy-to-clipboard buttons** for command examples and code snippets.
- **Progress tracking** with “Mark as learned” controls.
- **Local progress persistence** using browser `localStorage`.
- **Responsive layout** with a desktop sidebar and mobile navigation menu.
- **Accessibility-friendly interactions**, including visible focus states and reduced-motion support.
- **Security-focused explanations** of common vulnerabilities and their defenses.


## Learning Modules

### Web Vulnerabilities

The dedicated web-vulnerabilities module explains six common weaknesses:

1. SQL Injection
2. Insecure Direct Object Reference (IDOR)
3. Path Traversal
4. Broken Access Control
5. Reflected Cross-Site Scripting (XSS)
6. Command Injection


## Getting Started

### Run Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/MadhumithaS-29/TrainerWebsite.git
   cd TrainerWebsite
   ```

2. Open either HTML file directly in a modern web browser:

   ```text
   Cybersecurity Portal.html
   Web Vulnerabilities - Cybersecurity Portal.html
   ```

   Alternatively, start a local HTTP server:

   ```bash
   python -m http.server 8000
   ```

3. Open the relevant page:

   ```text
   http://localhost:8000/Cybersecurity%20Portal.html
   http://localhost:8000/Web%20Vulnerabilities%20-%20Cybersecurity%20Portal.html
   ```

## Technology Stack

- HTML5
- CSS3
- Vanilla JavaScript
- Browser `localStorage` API

## Contributing

Contributions are welcome. When proposing changes:

1. Keep the project dependency-free where practical.
2. Preserve the standalone HTML-file experience.
3. Use clear, accessible markup and keyboard-friendly controls.
4. Keep cybersecurity examples safe and focused on authorized learning.
5. Test the pages in both desktop and mobile layouts.
