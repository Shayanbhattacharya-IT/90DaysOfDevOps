1. Include at least 20 commands with one‑line usage notes

| No. | Command        | Description                                                | Example                           |
| --- | -------------- | ---------------------------------------------------------- | --------------------------------- |
| 1   | `ls`           | List files and directories                                 | `ls`                              |
| 2   | `ls -l`        | List files in long format (permissions, owner, size, date) | `ls -l`                           |
| 3   | `ls -a`        | Show all files, including hidden files                     | `ls -a`                           |
| 4   | `pwd`          | Print the current working directory                        | `pwd`                             |
| 5   | `whoami`       | Display the current logged-in user                         | `whoami`                          |
| 6   | `sudo su`      | Switch to the root user                                    | `sudo su`                         |
| 7   | `mkdir`        | Create a new directory                                     | `mkdir project`                   |
| 8   | `cd`           | Change the current directory                               | `cd project`                      |
| 9   | `cp`           | Copy files or directories                                  | `cp file1.txt backup.txt`         |
| 10  | `mv`           | Move or rename files/directories                           | `mv file.txt newfile.txt`         |
| 11  | `rmdir`        | Remove an empty directory                                  | `rmdir project`                   |
| 12  | `rm -r`        | Remove a directory and its contents recursively            | `rm -r project`                   |
| 13  | `rm`           | Remove a file                                              | `rm file.txt`                     |
| 14  | `rm -rf`       | Forcefully remove a directory and all its contents         | `rm -rf project`                  |
| 15  | `grep`         | Search for text inside files                               | `grep "error" logs.txt`           |
| 16  | `cat`          | Display or concatenate file contents                       | `cat notes.txt`                   |
| 17  | `vim` / `nano` | Open a text editor to create or edit files                 | `vim file.txt` or `nano file.txt` |
| 18  | `touch`        | Create an empty file or update its timestamp               | `touch test.txt`                  |
| 19  | `systemctl`    | Manage Linux services (systemd)                            | `systemctl status nginx`          |
| 20  | `clear`        | Clear the terminal screen                                  | `clear`                           |

2. Add 3 networking commands (ping, ip addr, dig, curl, etc.)

| No. | Command   | Description                                                                 | Example                    |
| --- | --------- | --------------------------------------------------------------------------- | -------------------------- |
| 21  | `ping`    | Checks connectivity to a host by sending ICMP echo requests                 | `ping google.com`          |
| 22  | `ip addr` | Displays IP addresses and network interface details                         | `ip addr`                  |
| 23  | `curl`    | Transfers data from or to a server; commonly used to test APIs and websites | `curl https://example.com` |

Additional Commands

| Command                 | Purpose                                                     |
| ----------------------- | ----------------------------------------------------------- |
| `dig google.com`        | Query DNS records                                           |
| `nslookup google.com`   | Look up DNS information                                     |
| `traceroute google.com` | Trace the network path to a host                            |
| `ss -tuln`              | Display listening TCP/UDP ports                             |
| `netstat -tulnp`        | Show active connections and listening ports (older systems) |
| `hostname -I`           | Display the system's IP address                             |
| `ip route`              | Show the routing table                                      |

3. Group commands by category.

# 📂 File & Directory Management

| Command  | Description                          | Example                   |
| -------- | ------------------------------------ | ------------------------- |
| `ls`     | List files and directories           | `ls`                      |
| `ls -l`  | Long listing format                  | `ls -l`                   |
| `ls -a`  | Show hidden files                    | `ls -a`                   |
| `pwd`    | Show current directory               | `pwd`                     |
| `mkdir`  | Create a directory                   | `mkdir project`           |
| `cd`     | Change directory                     | `cd project`              |
| `cp`     | Copy files/directories               | `cp file1.txt backup.txt` |
| `mv`     | Move or rename files                 | `mv old.txt new.txt`      |
| `rmdir`  | Remove an empty directory            | `rmdir test`              |
| `rm`     | Delete a file                        | `rm file.txt`             |
| `rm -r`  | Delete a directory recursively       | `rm -r folder`            |
| `rm -rf` | Force delete a directory recursively | `rm -rf folder`           |
| `touch`  | Create an empty file                 | `touch notes.txt`         |

---

# 📄 File Viewing & Editing

| Command | Description              | Example                |
| ------- | ------------------------ | ---------------------- |
| `cat`   | Display file contents    | `cat file.txt`         |
| `grep`  | Search for text in files | `grep "error" app.log` |
| `vim`   | Open Vim editor          | `vim file.txt`         |
| `nano`  | Open Nano editor         | `nano file.txt`        |

---

# 👤 User & System Information

| Command   | Description           | Example   |
| --------- | --------------------- | --------- |
| `whoami`  | Display current user  | `whoami`  |
| `sudo su` | Switch to root user   | `sudo su` |
| `clear`   | Clear terminal screen | `clear`   |

---

# ⚙️ Service Management

| Command             | Description             | Example                   |
| ------------------- | ----------------------- | ------------------------- |
| `systemctl status`  | Check service status    | `systemctl status nginx`  |
| `systemctl start`   | Start a service         | `systemctl start nginx`   |
| `systemctl stop`    | Stop a service          | `systemctl stop nginx`    |
| `systemctl restart` | Restart a service       | `systemctl restart nginx` |
| `systemctl enable`  | Enable service at boot  | `systemctl enable nginx`  |
| `systemctl disable` | Disable service at boot | `systemctl disable nginx` |

---

# 🌐 Networking Commands

| Command       | Description                              | Example                    |
| ------------- | ---------------------------------------- | -------------------------- |
| `ping`        | Test network connectivity                | `ping google.com`          |
| `ip addr`     | Show IP addresses and network interfaces | `ip addr`                  |
| `curl`        | Send HTTP requests or test APIs          | `curl https://example.com` |
| `dig`         | Query DNS records                        | `dig google.com`           |
| `nslookup`    | Look up DNS information                  | `nslookup google.com`      |
| `traceroute`  | Trace the route packets take             | `traceroute google.com`    |
| `hostname -I` | Display the system's IP address          | `hostname -I`              |
| `ip route`    | Display the routing table                | `ip route`                 |
| `ss -tuln`    | Show listening TCP/UDP ports             | `ss -tuln`                 |

---

# 🚀 Most Common Commands for DevOps & Application Support

* `pwd`
* `ls -la`
* `cd`
* `mkdir`
* `cp`
* `mv`
* `rm -rf`
* `cat`
* `grep`
* `touch`
* `vim` / `nano`
* `whoami`
* `sudo su`
* `systemctl`
* `ping`
* `ip addr`
* `curl`
* `dig`
* `hostname -I`
* `ss -tuln`

4. Keep it concise and readable
