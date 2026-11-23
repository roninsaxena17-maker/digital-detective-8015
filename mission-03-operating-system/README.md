# Mission 3 — Understand the Operating System

## 1. Task / objective
Explore the operating system, running processes, storage, file paths, permissions and the responsibilities of an operating system.

## 2. Work completed

### Task 3.1 — System exploration

Operating system: macOS
Version: 27.2.1
Build: 26B131

Storage information from df -h /:
- Total filesystem size: 460 GiB
- Used: 13 GiB
- Available: 313 GiB
- Capacity: 4%

The top command reported 882 processes in the system snapshot.

### Task 3.2 — Processes and PIDs

A process is a program currently being executed by the operating system. Each process is assigned a Process ID (PID).

Examples observed:
- PID 1: launchd
- logd: System logging service
- configd: System configuration service
- powerd: Power management service

### Task 3.3 — Paths and permissions

I navigated from the project root into the Mission 3 folder using cd and returned to the parent directory using cd ..

An absolute path starts from the filesystem root. A relative path is interpreted from the current working directory.

File permissions observed for terminal-practice/notes.txt:

-rw-r--r--

The owner has read and write permissions. Group members and others have read permission. The file does not have execute permission.

### Task 3.4 — Operating system responsibilities

| Responsibility | Explanation | Example |
|---|---|---|
| Process management | Manages running programs and CPU allocation. | Running multiple applications. |
| Memory management | Allocates RAM to programs. | Allocating memory to a browser. |
| Device management | Manages hardware devices. | Managing keyboard and printer. |
| File management | Organises files and directories. | Saving documents in folders. |
| User interface | Provides ways for users to interact with the computer. | Desktop and Terminal. |
| Security and permissions | Controls access to files and system resources. | Restricting file access. |

## 3. Commands / tools used
- sw_vers: Displays macOS version and build.
- whoami: Displays the current user.
- df -h /: Displays filesystem storage information.
- top -l 1: Displays a system activity snapshot.
- ps: Lists processes.
- pwd: Displays the current directory.
- cd: Navigates between directories.
- ls -l: Displays file permissions and details.

## 4. My understanding
The operating system manages hardware and software resources. It manages processes, memory, files, devices, security and the user interface. Processes are running programs with PIDs. Paths identify locations of files, while permissions determine who can read, write or execute them.

## 5. Difficulties faced
No major difficulties during system exploration.

## 6. How I resolved them
I used Terminal commands to inspect system information, processes, storage and permissions.

## 7. Evidence / files
- System version output from sw_vers.
- Storage information from df.
- Process information from top and ps.
- File permissions from ls -l.
- Directory navigation using pwd and cd.

Personal identifiers have been excluded from the documentation.

## 8. Commit details
To be updated after committing and pushing this mission.
