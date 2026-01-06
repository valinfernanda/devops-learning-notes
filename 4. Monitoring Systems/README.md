Task

1. Prepare 2 servers
(Can be two separate VMs, cloud instances, or even local machines/containers – as long as they can communicate over the network.)

2. On Server 2: Install Node Exporter
Node Exporter will collect and expose system metrics (CPU, memory, disk, etc.) from Server 2.

3. On Server 1: Install Prometheus
Prometheus will act as the monitoring server that scrapes and stores metrics.

4. Connect Node Exporter on Server 2 to Prometheus on Server 1
Configure Prometheus to scrape metrics from the Node Exporter running on Server 2.

5. Retrieve and display memory usage data from Server 2 via Prometheus
Access the Prometheus web interface (or use a query) on Server 1 to view real-time memory usage metrics collected from Server 2.
