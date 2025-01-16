# Authenticated vs Unauthenticated
Scanning Windows and Linux virtual VM: Authenticated vs Unauthenticated

In this Project we will go over scanning Windows in the Authenticated form and Unauthenticated. 

Key Benefits of performing these scans:

Authenticated scans use login credentials to check inside a system for vulnerabilities like weak passwords, missing updates, or misconfigurations, giving a detailed view of internal risks. 

Unauthenticated scans look at the system from the outside, identifying weaknesses visible to attackers, like open ports or outdated software.

In simple terms:
Authenticated scans show what a trusted user (or an attacker with access) can see and exploit.

Unauthenticated scans show what an outsider can see and try to attack.

Using both ensures you secure both the inside and outside of your systems.

UNAUTHENTICATED SCAN WINDOWS:

![Screenshot 2025-01-14 185832](https://github.com/user-attachments/assets/aa2f7853-df01-4c55-905e-6b6daac065bf)

AUTHENTICATED SCAN WINDOWS:

![Screenshot 2025-01-14 185917](https://github.com/user-attachments/assets/6700282c-240b-4b36-8083-ec8a2c1cee1d)


UNAUTHENTICATED LINUX:

<img width="800" alt="Screenshot 2025-01-15 at 2 33 08 PM" src="https://github.com/user-attachments/assets/42cc571e-3ae3-4532-80d0-f57ebdb0d52f" />

AUTHENTICATED LINUX:

<img width="800" alt="Screenshot 2025-01-15 at 2 33 58 PM" src="https://github.com/user-attachments/assets/d92904b2-10c7-444c-a5b8-9c0935928d2f" />



You might be asking yourself why fix stuff a malicious actor can't see? Well, if an attacker can gain some level of access and begins to elevate their access they will be able to start seeing more stuff and eventually take advantage of vulnerabilities they can find. 

By proactively practicing these scans we can fix vulnerabilites and minimize the attack surface. 
