## 1. Understanding Ports and Port Numbers

* **Ports** act like gateways into a system, each linked to a specific service or application.
* **Port number**: The unique identifier for that gateway.
* **Port ranges**:

  * **0–1023** → Well-known ports (e.g., HTTP, FTP, SSH)
  * **1024–49151** → Registered ports (assigned to particular applications)
  * **49152–65535** → Dynamic/Private ports (temporary, often for outbound connections)

---

## 2. Common Service Ports (Example: FTP – Port 21)

* **FTP (File Transfer Protocol)**:

  * Port: **21** (control channel)
  * Used to transfer files between client and server.
  * Sends data in plain text (not secure).
  * **Secure alternative**: SFTP over SSH (Port 22).
* Other important ports to remember:

  * **HTTP** → Port 80
  * **HTTPS** → Port 443
  * **SSH** → Port 22

---

## 3. Linux User Types

* **Root user**: Full administrative privileges — unrestricted control.
* **Regular user**: Standard account for everyday tasks.
* **Service account**: Used by software or services, not humans.

---

## 4. Privilege Escalation in Linux

* Definition: Gaining access rights beyond what you’re normally granted.
* Types:

  * **Vertical**: Going from a regular user to root.
  * **Horizontal**: Accessing another user’s data without gaining higher privileges.
* Common techniques:

  * Exploiting misconfigured `sudo` permissions.
  * Weak or incorrect file permissions.
  * Exploiting kernel or software vulnerabilities.

---

## 5. Useful Linux Command – `watch`

* Runs a command repeatedly and updates the output in real-time.
* **Syntax**:

  ```bash
  watch [options] command
  ```
* **Example**:

  ```bash
  watch -n 5 date
  ```

  Displays the date/time every 5 seconds.

---

## 6. Security Operations Center (SOC)

* A centralized hub for monitoring, detecting, and responding to security incidents.
* **Roles inside a SOC**:

  * **Tier 1 Analyst**: Initial alert triage and response.
  * **Tier 2 Analyst**: In-depth investigation and analysis.
  * **Incident Responder**: Containment and recovery after a confirmed threat.

---

## 7. Cybersecurity Learning Platforms (Example: TryHackMe)

* Provide hands-on cybersecurity labs and guided learning exercises.
* Useful for practicing: reconnaissance, exploitation, privilege escalation, and more.
* Examples: TryHackMe, HackTheBox, OverTheWire.
