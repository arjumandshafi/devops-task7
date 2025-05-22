TASK 7: Monitor System Resources Using Netdata

Objective:

Install Netdata using Docker and visualize system and app performance metrics like CPU, RAM, disk, and containers.

Tools Required:

- Docker Desktop

- Terminal

- Netdata (Docker image)

- Web browser

steps:

1. Ensure Docker Desktop is running.

2. Run Netdata container using this command:
 
   docker run -d --name=netdata -p 19999:19999 --cap-add=SYS_PTRACE --security-opt apparmor=unconfined netdata/netdata

Open your browser and visit:

 http://localhost:19999

 you will see Netdata dashboard which is showing charts for:
 
 CPU usage

Memory usage

Disk I/O

Network activity

Docker container performance

Deliverables:

Screenshot of the Netdata dashboard showing system metrics.
