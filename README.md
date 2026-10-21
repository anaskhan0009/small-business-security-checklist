# Small Business Security Checklist — 25-Point Audit & Score

A practical security audit built for businesses without an IT department: **25 concrete protections** across accounts & access, devices & updates, network & Wi-Fi, payments & data, and staff habits. Each item says what to do *and why it matters*. Your **score and grade update live**, a **critical-first priority list** shows what to fix next, and a local account stores one audit per business or location — complete with action items, owners and due dates.

**Live Demo:** https://anaskhan0009.github.io/small-business-security-checklist/

## Features

- **Local account system** — sign up / log in on this device (passwords stored only as salted SHA-256 hashes, never plain text), continue as guest, per-account data separation, account deletion, and Export / Import of your records as JSON
- **Full record manager (CRUD)** — create, view, edit and delete your own saved records; the core tool works fully without an account, signing in unlocks saving for audits per business/location, including action items with owners and due dates
- **25 real-world protections** written for owners, not engineers — shared logins, same-day leaver access removal, guest Wi-Fi separation, invoice-fraud double-checks
- **Live score & grade** with a progress bar, and a **priority fix list** (top 6 gaps, ★ criticals first)
- **Auto-save** — checklist progress persists on the device while you work

## How to Use

1. Work through the 25 items honestly — tick only what is truly in place.
2. Read your score and the priority list; the ★ items stop the most damage per hour spent.
3. Save the audit, then edit the record: add the business name and turn priorities into action items with owners and due dates.
4. Re-audit every 6 months, and whenever staff, systems or premises change.

## Why Small Businesses Are Targeted

Attackers do not pick victims by size — they scan for open doors: exposed remote desktop, reused passwords, unpatched laptops, one shared 'admin' login. Small businesses hold money, customer data and trusted email addresses, usually with none of a big company's defences. These 25 items close the doors that automated attacks actually walk through, in the order that matters.

## Ethical Use

This is a **defensive, educational tool** — it only ever helps you understand and improve your own security. Nothing here can be used to attack, track or deceive anyone else.

## Tech

Single self-contained `index.html` — HTML, CSS, vanilla JavaScript, WebCrypto (salted SHA-256 password hashing), localStorage persistence. No servers, no tracking, no external requests.

---

Built by **Dinal Studios** — free cyber security tools and web apps.
GitHub: https://github.com/anaskhan0009
