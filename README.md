# DevOps Tooling Website Solution

This documentation outlines the step-by-step process of setting up a network file system (NFS) server on Red Hat Enterprise Linux 9, configuring MySQL on an Ubuntu server, and deploying a tooling website across multiple web servers. The goal is to ensure a scalable, fault-tolerant infrastructure that maintains data consistency across web servers using shared storage, while keeping the system stateless.

This project involved setting up logical volumes on the NFS server, configuring Apache and PHP, and deploying a website that connects to a MySQL database. The setup was done using AWS EC2 instances and aimed to ensure seamless functionality and shared storage solutions.


## STEPS INVOLVED

- [Step 1: Prepare NFS Server](#step-1-prepare-nfs-server)

- [Step 2: Configure Database Server](#step-2-configure-database-server)
- [Step 3: Prepare the Web Servers](#step-3-prepare-the-web-servers)
