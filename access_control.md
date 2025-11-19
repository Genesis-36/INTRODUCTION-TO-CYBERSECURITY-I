## 🛡️ I. Threat Types (Who are the attackers?)

In cybersecurity, different people can become attackers, and they all have different goals and skill levels:

| Threat Actor        | Who They Are                                   | What They Want                                   |
| ------------------- | ---------------------------------------------- | ------------------------------------------------ |
| Script Kiddies      | Unskilled users using ready-made hacking tools | Fun, attention, or minor disruption              |
| Hacktivists         | Activists using hacking to promote ideas       | Spread political or social messages              |
| Organized Crime     | Professional cybercriminals                    | Money — through fraud, ransomware, or data theft |
| Nation-State Actors | Government-backed hackers                      | Espionage, sabotage, or cyberwarfare             |
| Insiders            | Employees or contractors                       | Cause damage (intentionally or by mistake)       |
| Competitors         | Rival companies                                | Steal business secrets or get an advantage       |

👉 **Why it matters:**
Different attackers require **different defense strategies**. For example, monitoring employees helps stop insiders, while strong encryption helps block nation-state attacks.

---

## 🔐 II. Types of Access Control (How to control who enters what?)

Access control decides **who can access a system, and what they can do inside**.
Here are the main types, explained simply:

| Access Control Type | Easy Explanation                           | Example                                        |
| ------------------- | ------------------------------------------ | ---------------------------------------------- |
| DAC                 | Owner controls access                      | You share a file with someone manually         |
| MAC                 | System enforces strict rules               | Government/classified systems                  |
| RBAC                | Access based on job role                   | HR can see employee records                    |
| ABAC                | Uses attributes (role, location, time)     | Only allow login from office during work hours |
| Rule-Based          | Access follows system rules                | Firewall blocks all external traffic           |
| IBAC                | Access based on identity (specific person) | Only “John Doe” can access                     |
| Time-Based          | Access allowed only at certain times       | Employees access system from 9am–5pm           |
| Physical Access     | Control physical entry                     | Fingerprint scanner to enter server room       |

👉 Companies often **combine** these types to increase security.

---

## 🧾 AAA: Authentication, Authorization, Accounting

| Term           | Meaning                               | Example                                |
| -------------- | ------------------------------------- | -------------------------------------- |
| Authentication | “Are you really who you say you are?” | Login with password                    |
| Authorization  | “What are you allowed to do?”         | User can view but not edit files       |
| Accounting     | “What did you do?”                    | System logs who accessed what and when |

---

### Identification vs Authentication vs Authorization

| Step           | What it does                | Example                 |
| -------------- | --------------------------- | ----------------------- |
| Identification | Claiming an identity        | Entering username       |
| Authentication | Verifying identity          | Entering password       |
| Authorization  | Allowing or denying actions | Can/cannot delete files |

---

## 🔑 Multifactor Authentication (MFA)

MFA improves security by requiring **two or more types of proof** to access an account.

| Factor Type        | Description   | Examples                            |
| ------------------ | ------------- | ----------------------------------- |
| Something You Know | Knowledge     | Password, PIN, security question    |
| Something You Have | Physical item | OTP from phone, smart card, token   |
| Something You Are  | Biometric     | Fingerprint, face scan, iris, voice |

👉 Using at least **2 of these together** increases security (e.g., password + OTP).

---

## 🔍 Gap Analysis

Gap analysis helps a company find **what security they currently have** vs **what security they should have**.

👉 It answers the question:
**“Where are we now, and what do we need to improve?”**

It helps detect security weaknesses, plan improvements, and protect systems better.

---

## 🕵️ Honeypots, Honeyfiles, and Honeynets

| Term      | Explanation          | Purpose                                              |
| --------- | -------------------- | ---------------------------------------------------- |
| Honeypot  | Fake system          | Attract hackers and study their behavior             |
| Honeyfile | Fake file            | Alerts when accessed, detects data theft or insiders |
| Honeynet  | Network of honeypots | Study advanced multi-stage attacks                   |

💡 These tools do **not stop attacks**, but they help in **detecting and analyzing** attackers.

---

## 📜 Approval Process

Before applying any **security changes**, an organization must first get **permission**.

This ensures:
✔ Changes are reviewed
✔ Risks are checked
✔ They follow company policy
✔ No damage to systems

---

## 🔁 Change Management Considerations

When making changes (like updates, patches, new software), we must:

| Consideration        | What it means                            |
| -------------------- | ---------------------------------------- |
| Risk Assessment      | Check possible dangers before change     |
| Documentation        | Record all steps and reasons             |
| Testing & Validation | Test in a lab before real use            |
| Rollback Plan        | Have a backup plan if things go wrong    |
| Monitoring           | Watch system after changes               |
| Communication        | Inform users and staff about the changes |

---

## 🛠️ Technical Implications (Things to consider during changes)

| Term                        | Meaning                                                   |
| --------------------------- | --------------------------------------------------------- |
| Allow/Deny List             | List of devices/users allowed or blocked                  |
| Restricted Activities       | Actions that users are **not allowed** to do              |
| Downtime                    | Time when system is offline                               |
| Service/Application Restart | Restart needed after update                               |
| Legacy Applications         | Old systems that may not support new security             |
| Dependency                  | One system depends on another, so changes can affect both |

💡 These help companies avoid system failures during updates.
