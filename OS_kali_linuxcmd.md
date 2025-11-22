## I. Approval Process (In Cybersecurity)

Think of the **approval process** like getting permission before making changes at home.
If you want to move the TV or change the Wi-Fi password, you ask your parents first.

In cybersecurity, before making any security changes—like upgrading a system, giving someone admin access, or installing a firewall—you must **get approval** from the right people (security team, management, compliance officers).

### Why?

* To make sure the change is **safe**
* To check if it **follows rules and policies**
* To avoid **security risks and mistakes**

This process ensures every change is **well planned, reviewed, and authorized**.

---

## II. Change Management – Extra Things to Consider

Before making any changes, we must plan carefully, just like preparing before fixing electrical wiring at home.

| Term                | Simple Explanation                                                               |
| ------------------- | -------------------------------------------------------------------------------- |
| **Risk Assessment** | Check what could go wrong if we make this change.                                |
| **Documentation**   | Write down what change is made, when, how, and why — so it can be tracked later. |
| **Testing**         | Try the change in a test/lab environment first to make sure it works fine.       |
| **Rollback Plan**   | A backup plan — what to do if the change fails. Like Ctrl+Z (undo).              |
| **Monitoring**      | Watch the system after changes to detect problems or attacks.                    |
| **Communication**   | Inform everyone affected — users, managers, IT team — before making the change.  |

---

## III. Standard Operating Procedures (SOPs)

An **SOP is like a recipe or instruction manual** for how to do a task the right way every time.

It helps workers follow a **standard method**—so they don’t make mistakes.

### Key parts of an SOP:

* **Title and Purpose** – What the SOP is about and why it matters.
* **Scope** – Where and when it applies.
* **Roles and Responsibilities** – Who does what.
* **Procedure Steps** – Step-by-step instructions.
* **Documentation and Forms** – Any records needed.
* **References** – Related policies or documents.
* **Review and Updates** – How it will be kept up to date.

📝 SOPs help make work **consistent, accurate, and safe**.

---

## IV. Technical Implications (Things to Consider When Making Technical Changes)

| Term                            | Explained with Example                                                                           |
| ------------------------------- | ------------------------------------------------------------------------------------------------ |
| **Allow/Deny List**             | Like a party guest list – tells who is allowed and who is blocked. Used to control access.       |
| **Restricted Activities**       | Things users are not allowed to do, like installing apps or accessing certain files.             |
| **Downtime**                    | When a system is offline for maintenance or updates. Like when your phone restarts for updates.  |
| **Service/Application Restart** | Restarting a system or application to apply changes. Like restarting Wi-Fi router to fix issues. |
| **Legacy Applications**         | Old applications that may not support modern features but still used by businesses.              |
| **Dependency**                  | When one system depends on another. If one fails, the others may also be affected.               |

---

# 🖥️ OPERATING SYSTEMS

## I. What is an Operating System (OS)?

An **OS is like a manager** of the computer.
It helps hardware and software communicate and work together.

It controls CPU, memory, files, applications, and user interactions.

---

## II. Main Functions of an OS

| Function                   | Simple Description                           |
| -------------------------- | -------------------------------------------- |
| **Process Management**     | Manages running programs (apps).             |
| **Memory Management**      | Gives each program its own space in RAM.     |
| **File System Management** | Helps you save, organize, and manage files.  |
| **Device Management**      | Handles devices like keyboard, printer, USB. |
| **User Interface**         | Lets you interact (GUI or CLI).              |

---

## III. Examples of Operating Systems

| Type    | Examples                      |
| ------- | ----------------------------- |
| Desktop | Windows, macOS, Linux         |
| Mobile  | Android, iOS                  |
| Server  | Red Hat, Unix, Windows Server |

---

## IV. Overview of Major Operating Systems

| Feature   | Linux             | Unix               | Windows            |
| --------- | ----------------- | ------------------ | ------------------ |
| Cost      | Free              | Expensive          | Licensed           |
| Interface | CLI & GUI         | Mostly CLI         | GUI mainly         |
| Security  | Very High         | High               | Moderate           |
| Use       | Servers, desktops | Enterprise servers | Business, personal |

---

# 🧮 Virtual Machines (VMs)

A **Virtual Machine** is like creating a **computer inside another computer**.

You can run Windows inside a Linux system, or run multiple OS at the same time — all virtually.

Useful for:
✔ Testing
✔ Running old software
✔ Training in cybersecurity
✔ Creating isolated environments

---

# 🛡️ What is Kali Linux?

**Kali Linux** is a special type of Linux for **ethical hacking and cybersecurity testing**.

It includes tools for:

* Network scanning (Nmap)
* Password cracking
* Forensics
* Vulnerability testing

It is mostly used by **ethical hackers and penetration testers**.

---

# 🖥️ What is the Terminal?

The **terminal** is a text-based interface where you type commands to control the computer.

Like talking to the computer in its language.

### How to open it?

* Click terminal icon
* Search “Terminal”
* Press **Ctrl+Alt+T**

---

# 📂 Basic Kali Linux Commands (Beginner Level)

### 💡 Navigation Commands

| Command | Purpose               |
| ------- | --------------------- |
| ls      | List files            |
| cd      | Change directory      |
| pwd     | Show current location |

### ✍ File & Directory Commands

| Command | Purpose        |
| ------- | -------------- |
| mkdir   | Make folder    |
| touch   | Create file    |
| rm      | Delete file    |
| cp      | Copy files     |
| mv      | Move or rename |

### 🌐 Network Commands

| Command  | Used for                  |
| -------- | ------------------------- |
| ifconfig | View IP address           |
| ping     | Check internet connection |
| netstat  | See open ports            |

### ⚙ System Info

| Command  | Purpose             |
| -------- | ------------------- |
| uname -a | Show system info    |
| whoami   | Show logged-in user |
| free -m  | Show memory usage   |

### 🛠 Package Management

| Command              | Purpose             |
| -------------------- | ------------------- |
| apt-get update       | Update package list |
| apt-get upgrade      | Upgrade apps        |
| apt-get install nmap | Install app         |

### 📊 Process Management

| Command  | Purpose                  |
| -------- | ------------------------ |
| ps aux   | Show running processes   |
| kill PID | End process              |
| top      | Real-time resource usage |
