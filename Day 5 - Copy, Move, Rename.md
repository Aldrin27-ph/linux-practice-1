# Linux Commands I Learned Today (Jan 6, 2026)

## Networking Basics

Networking knowledge helps explain why cloud services sometimes fail:

- **EC2 not accessible** – Port 22 (SSH) might be blocked.  
- **Website not loading** – Ports 80 (HTTP) or 443 (HTTPS) might be blocked.  
- **Domain broken** – DNS issues.  
- **Can't connect** – Problems with IP or security groups.

---

## `cp` Command – Copy Files and Directories

The `cp` command is used to **copy files or directories**. It is useful for backups, copying configuration files, or preparing deployment files.

### Key Options

- `cp -r` – Copy directories and their contents recursively.  
- `cp -p` – Preserve file permissions, ownership, and timestamps.  
- `cp -rp` or `cp -pr` – Copy directories recursively **and** preserve permissions, ownership, and timestamps.  

### Notes

- The original file or directory remains in place.  
- You can rename files while copying.  


### Example

```bash
# Copy and rename a file
cp file.txt /home/aldrin_john/day5/newfile.txt
mv Command
The mv command allows you to move or rename files and directories.

Limitation: You cannot rename multiple files at once in a single command.

Unlike cp, mv does not need -r or -p:

Directories and files are moved as-is, including all contents.

Original permissions and timestamps are preserved automatically.

Example
bash
Copy code
# Move and rename a file
mv file.txt /home/aldrin_john/day5/newfile.txt
