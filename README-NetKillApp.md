# NetKillApp

NetKillApp is a Java-based network monitoring and process management tool designed for advanced users who want to track and control network connections on their system. This software allows you to:

- View active network connections per application.
- Track historical connections over time.
- Terminate suspicious or unwanted connections safely.
- Inspect the geographic location of remote IPs.
- Visualize the data in a dynamic, visually appealing interface with animated background effects.

## Features

1. **Active Connections Table**  
   Displays all currently active applications and their network connections. Right-click to expand or collapse the connection list for each application.

2. **History Tracking**  
   Maintains a historical record of apps and their connections. You can review which applications connected to which IPs over time.

3. **Termination of Connections**  
   Allows safe termination of processes or connections directly from the interface.

4. **Geo IP Lookup**  
   Double-clicking an IP in the connections table opens a small map showing the approximate location of the remote host.

5. **Custom UI**  
   The user interface features a dynamic starry background for visual appeal, inspired by advanced monitoring dashboards.

6. **Cross-platform with Java**  
   Written entirely in Java, NetKillApp can run on any system with Java 17+ installed.

---

## Usage

1. Run the JAR file:

```bash
java -jar NetKillApp.jar
