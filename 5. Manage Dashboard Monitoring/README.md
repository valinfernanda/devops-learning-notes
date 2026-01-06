Task:
1. Install VM and Configure Nginx
Install one VM, then configure Nginx.
Create a simple index.html file containing:
<h1>Hello, this is my first website!</h1>
Testing: Access http://IP_VM and make sure the page appears.

2. Monitoring Memory Usage
Set up memory usage monitoring on the VM using Node Exporter (for metric collection), Prometheus (as the data source), and Grafana (for visualization).

3. Memory Usage Alert
Create an alert when memory usage exceeds a specified threshold.
Send the alert notification to Discord.

4. Web Server Monitoring with Uptime Kuma
Configure web server monitoring using Uptime Kuma.
If http://IP_VM goes down, send an alert notification to Discord.