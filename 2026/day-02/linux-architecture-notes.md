📅 Day 02 – Linux Fundamentals

## #90DaysOfDevOps

Linux is the **foundation of DevOps engineering**. Almost everything in DevOps—servers, containers, CI/CD pipelines, cloud instances, Kubernetes nodes—runs on Linux.  
On **Day 02**, I focused on understanding **how Linux works internally** and practiced essential commands to build a strong base.

## 🧠 What I Learned Today

### 🔹 How the Linux Operating System Works

Linux follows a layered architecture:

1.  **Hardware** – CPU, Memory, Disk, Network
2.  **Kernel** – Core of the OS
3.  **Shell** – Interface between user and kernel
4.  **Applications** – User programs and services

When a user runs a command:

*   The **shell** interprets it
*   The **kernel** executes it by interacting with hardware
*   Output is returned back to the user


### 🔹 How Applications Are Processed in Linux

*   Every running program is called a **process**
*   Each process has a unique **PID (Process ID)**
*   The kernel manages:
    *   CPU scheduling
    *   Memory allocation
    *   Process lifecycle (start, run, stop)

You can view running processes using tools like:

```bash
top
htop
```


### 🔹 Kernel & Shell Explained

#### ✅ Kernel

*   The **core of Linux**
*   Manages:
    *   CPU
    *   Memory
    *   Disk
    *   Network
    *   Processes

The kernel runs in **privileged mode** and directly interacts with hardware.

#### ✅ Shell

*   A **command-line interface**
*   Takes user commands and passes them to the kernel
*   Examples: `bash`, `zsh`, `sh`

## 🧩 Core Components of Linux

| Component        | Description                         |
| ---------------- | ----------------------------------- |
| Kernel           | Manages hardware & system resources |
| Shell            | User interface to interact with OS  |
| File System      | Organizes data in directories       |
| System Utilities | Tools like `ls`, `cat`, `top`       |
| User Space       | Area where applications run         |


## ⚙️ systemd & PID 1

### 🔹 What is systemd?

*   **systemd** is the default **init system** in modern Linux distributions
*   It is responsible for:
    *   Booting the system
    *   Starting services
    *   Managing background processes (daemons)

### 🔹 What is PID 1?

*   The **first process** started by the kernel
*   Always has **PID = 1**
*   In modern systems, PID 1 is usually `systemd`
*   If PID 1 stops, the system crashes

Check PID 1 using:

```bash
ps -p 1
```


## 🛠️ Linux Commands Practiced (Hands-On)

### 🔹 System Information

```bash
uname -r              # Shows kernel version
cat /etc/os-release   # OS distribution details
```


### 🔹 File Operations

```bash
touch demo.txt        # Create a file
cat demo.txt          # View file content
vim demo.txt          # Edit using vim
nano demo.txt         # Edit using nano
head -n 1 demo.txt    # First line of file
tail -n 1 demo.txt    # Last line of file
```

### 🔹 Directory & Listing Commands

```bash
ls                    # List files
ls -l                 # Detailed listing
mkdir demo_dir        # Create directory
```

### 🔹 Process Monitoring

```bash
top                   # Real-time process monitoring
htop                  # Enhanced process viewer
```


### 🔹 Linux Paths & Permissions

```bash
/     # Root directory
~     # Home directory
sudo  # Execute commands as superuser
```

### 🔹 User & Group Management

```bash
useradd username            # Create a user
groupadd groupname          # Create a group
usermod -aG groupname username  # Add user to group
```
### 🔹 Pipes & Redirection

```bash
tail -n 1 demo.txt | tail -n 1
```

*   `|` (pipe) passes output of one command as input to another
*   Pipes are heavily used in **DevOps automation & scripting**

Linux knowledge is essential for:

*   Server administration
*   Docker & Kubernetes
*   CI/CD pipelines
*   Cloud infrastructure
*   Debugging production issues

Without Linux fundamentals, **DevOps tools are just abstractions**.
