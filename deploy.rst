Deploy BIG-IP VE in Google Cloud
--------------------------------

To use BIG-IP VE in Google Cloud, deploy it in your project.

1. In the Google Cloud Platform Console, in the top left corner, click the **Products & services** icon.
2. In the left pane, click **Cloud Launcher**.
3. In the **Search for solutions** field, type **F5** and from the results, click the image you want.
4. Click **Launch on Compute Engine**.

   .. image:: /_images/deploy1.png

|

5. Complete the fields. For the machine type, choose at least 2 vCPU and 4 GB memory. For each additional vCPU, add at least 2 GB of memory.

   .. image:: /_images/deploy2.png

   Note: Port 22 is enabled to allow SSH access to BIG-IP VE; port 8443 provides access to the web-based BIG-IP Configuration utility.

6. Click **Deploy**.

The instance is generated. Wait a few minutes before you use SSH to connect.