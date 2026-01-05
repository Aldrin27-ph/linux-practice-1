# Day 4: Linux Learning Notes

Today I learned several Linux commands and concepts that are essential for working as a Cloud Engineer.

---

## 1. `ls -al`

Lists directory contents in detail, including hidden files. Shows information like:

* File/folder size
* Owner and group
* Permissions
* Last modified date and time

Example:

```bash
ls -al
```

---

## 2. Resetting Password in WSL

If you forget your Linux user password on WSL:

1. Open PowerShell and run as root:

```powershell
wsl -u root
```

2. List users:

```bash
ls /home
```

3. Reset password:

```bash
passwd yourusername
```

> Password won’t appear as you type — this is for security. Type carefully and repeat.

---

## 3. `tree`

Displays a directory tree with main branches and sub-branches.

Example:

```bash
tree
```

---

## 4. `whoami`

Shows the current user logged in.

Example:

```bash
whoami
```

---

## 5. `sudo`

Grants temporary administrative privileges to execute commands that require root access, such as installing or updating packages.

Example:

```bash
sudo apt update
sudo apt install package-name
```

---

## 6. `chmod`

Controls file and directory permissions. Permissions determine **who can read, write, or execute a file**.

### Permission Types:

* `r` – read
* `w` – write
* `x` – execute

### Permission Groups:

* `u` – user (owner)
* `g` – group
* `o` – others

### Examples:

Create a file:

```bash
touch test.sh
```

Add read permission for the group:

```bash
chmod g+r test.sh
```

Remove read permission:

```bash
chmod g-r test.sh
```

Multiple changes in one command:

```bash
chmod u+rwx,g+rx,o+r test.sh
```

Or mix add/remove:

```bash
chmod u+rwx,g-r,o+r test.sh
```

---

## 7. `nano`

A simple text editor inside the terminal. You can create and edit files directly.

Example:

```bash
nano myfile.txt
```

---

These are the commands I learned today. I’m building a solid foundation for Linux administration, which is essential for Cloud Engineering.
