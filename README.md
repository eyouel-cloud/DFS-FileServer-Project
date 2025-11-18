# DFS File Server Lab

This lab demonstrates how to configure a resilient file sharing solution using:

- Windows File Server role
- DFS Namespaces
- DFS Replication
- NTFS and share permissions

## Objectives

- Install and configure two file servers (e.g., `FS01` and `FS02`).
- Create a DFS namespace: `\\corp.lab\Shares`
- Publish departmental folders: HR, IT, Finance.
- Configure NTFS and share permissions.
- Enable DFS replication between `FS01` and `FS02`.

## Example Steps

1. Install **File and Storage Services** on both servers.
2. Create local folders:
   - `D:\Shares\HR`
   - `D:\Shares\IT`
   - `D:\Shares\Finance`
3. Create the DFS namespace and add folders as targets.
4. Configure DFS Replication group between `FS01` and `FS02`.
5. Create AD groups (e.g., `HR-Share-RW`, `IT-Share-RW`) and assign permissions.
6. From a client, access `\\corp.lab\Shares` and validate access and failover.

This lab shows Windows storage administration and high-availability design using native tools.
## Author
## Eyouel Melaku ## 
