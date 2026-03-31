# Pintos Project Showcase

This repository presents my work on the Pintos operating systems project, including design documents, reports, and implementation summaries for the Threads, User Programs, and File System components.

## Overview

This project covered several core OS topics:

- Thread scheduling and synchronization
- Priority scheduling and donation
- User program support and system calls
- File system extensibility
- Buffer cache design
- Directory and path management

## My Main Contributions

### Threads
- Implemented an efficient alarm clock using a sleep list instead of busy waiting
- Implemented strict priority scheduling
- Implemented priority donation, including chained donation
- Made semaphores and condition variables priority-aware
- Preserved FIFO wake-up order among same-priority threads using a sequence-based tie breaker

### File System
- Implemented a 64-entry buffer cache
- Used a global cache lock plus per-entry locks
- Implemented clock replacement
- Added dirty write-back and shutdown flushing
- Worked on extensible files and indexed inode design

### User Programs
- Implemented file operation syscalls
- Worked on process control and cleanup logic
- Improved process exit handling and parent/child resource cleanup