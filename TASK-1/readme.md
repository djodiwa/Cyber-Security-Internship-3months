# Task 1: Understanding Cyber Security Basics & Attack Surface

## Introduction
Cyber security is all about protecting computers, networks, and data from harm or unauthorized access. This task helps build a strong base by explaining key ideas like the CIA triad, types of attackers, and attack surfaces. I'll use simple English to make it easy to understand. We'll cover real examples and map them to everyday apps.

## What is Cyber Security? Focus on the CIA Triad
Cyber security means keeping information safe, correct, and available when needed. The main idea is the **CIA triad**, which stands for:

- **Confidentiality**: This means keeping private information secret so only the right people can see it. For example, in banking, your account details like PIN or balance should not be seen by hackers. If someone steals your data, it could lead to identity theft.
- **Integrity**: This is about making sure data stays accurate and unchanged. On social media like Instagram or Facebook, your posts or photos should not be altered by others without your permission. If a hacker changes a company's financial records, it could cause big problems like wrong decisions.
- **Availability**: This ensures that systems and data are ready to use whenever needed. For instance, if a website like Netflix goes down due to an attack, users can't watch shows. In hospitals, if patient records aren't available, it could delay treatment.

These three work together—like in online shopping, confidentiality protects your card info, integrity ensures the order is correct, and availability keeps the site running.

## Different Types of Attackers
Attackers are people or groups who try to harm systems for different reasons. Here are common types:

- **Script Kiddies**: These are beginners, often young people, who use ready-made tools to attack without deep knowledge. They might hack a website just for fun or to show off, like defacing a school site.
- **Insiders**: These are people inside a company, like employees, who misuse access. For example, a disgruntled worker might leak customer data to get revenge.
- **Hacktivists**: Groups like Anonymous who hack to promote a cause, such as protesting against a government by taking down their website.
- **Nation-State Actors**: Governments or spies from countries who attack for espionage or sabotage. For example, a country might hack another nation's power grid to cause blackouts during a conflict.

Understanding these helps know why and how attacks happen.

## Common Attack Surfaces
An attack surface is any point where a system can be attacked. It's like doors and windows in a house—hackers look for weak ones. Common ones include:

- **Web Applications**: Websites like online stores where users log in. Attacks can happen through forms or links.
- **Mobile Apps**: Apps on phones, like games or banking apps, which can be tricked by fake updates.
- **APIs**: These are ways apps talk to each other, like how your weather app gets data from a server. If not secure, hackers can intercept info.
- **Networks**: Wi-Fi or office connections where data travels. Public Wi-Fi is risky because data can be snooped.
- **Cloud Infrastructure**: Services like AWS or Google Cloud where data is stored online. If misconfigured, anyone might access files.

Reducing attack surfaces means closing unnecessary "doors," like using strong passwords.

## OWASP Top 10 Vulnerabilities
OWASP (Open Web Application Security Project) lists the top 10 common web app risks. I checked their site to understand each:

1. **Broken Access Control**: Users can access things they shouldn't, like viewing others' accounts. Dangerous because it leads to data leaks.
2. **Cryptographic Failures**: Weak encryption, so data like passwords can be stolen easily during transmission.
3. **Injection**: Hackers inject bad code, like SQL injection to trick databases into giving out info.
4. **Insecure Design**: Bad planning from the start, making the whole system weak.
5. **Security Misconfiguration**: Wrong settings, like default passwords left unchanged.
6. **Vulnerable and Outdated Components**: Using old software with known bugs.
7. **Identification and Authentication Failures**: Weak logins, like easy-to-guess passwords.
8. **Software and Data Integrity Failures**: Code or data changed without checks, like tampered updates.
9. **Security Logging and Monitoring Failures**: Not tracking attacks, so they go unnoticed.
10. **Server-Side Request Forgery**: Servers tricked into accessing bad sites, leading to data exposure.

Each is dangerous because they let hackers in, steal data, or break systems. Reading them shows how small mistakes cause big issues.

## Mapping Daily-Used Applications to Attack Surfaces
We use apps every day, and each has possible weak points:

- **Email (like Gmail)**: Attack surface includes phishing links or attachments. Hackers send fake emails to steal login details.
- **WhatsApp**: End-to-end encryption helps, but attacks can happen via group invites or malware in shared files. Eavesdropping if phone is compromised.
- **Banking Apps (like mobile banking)**: Surfaces like login screens (weak passwords) or transactions (man-in-the-middle attacks stealing data in transit).

These show how everyday tools can be targeted if not careful.

## How Data Flows from User to Application to Server to Database
Data moves in steps, like a chain:

1. **User → Application**: You type info (e.g., login) into an app on your phone or computer.
2. **Application → Server**: The app sends data over the internet to a remote server.
3. **Server → Database**: Server processes it and stores or retrieves from a database.

Example: In online banking, you enter amount to transfer (user to app), app sends to bank server, server updates your balance in the database.

## Where Attacks Can Happen in This Flow
Attacks target weak links:

- **At User to Application**: Input tricks like entering code to crash the app (injection attacks).
- **Application to Server**: Data in transit can be intercepted if not encrypted (e.g., on public Wi-Fi).
- **Server to Database**: Server flaws let hackers query the database directly (SQL injection) or access without permission.
- **Overall**: Insider attacks or misconfigurations anywhere in the chain.

To stop this, use encryption, updates, and monitoring.

## Summary in My Own Words
Cyber security protects our digital world by ensuring data is private (confidentiality), unchanged (integrity), and always accessible (availability)—the CIA triad. Attackers range from kids playing around to serious governments, targeting surfaces like apps and networks. OWASP Top 10 highlights common dangers like weak access or bad code. Everyday apps like email or banking have risks in how data flows from us to servers. By understanding this, we can spot threats early and stay safer online. This builds awareness to avoid simple mistakes that lead to big hacks.



