# Unraid-Media-Server


<h2>Unraid Media Server Setup</h2>

<p>I built an Unraid server using the following hardware:</p>
<ul>
  <li><strong>Case:</strong> HP Compaq 6005 Pro SFF</li>
  <li><strong>CPU:</strong> AMD Athlon II x2 B24 3GHz</li>
  <li><strong>RAM:</strong> 32GB (upgraded from 4GB)</li>
  <li><strong>Storage:</strong> Two mismatched HDDs:
    <ul>
      <li><strong>Disk 1:</strong> ST1000DM003-1CH162_S1DDWJ5V - 1 TB</li>
      <li><strong>Disk 2:</strong> WDC_WD1002FBYS-18W8B0 - 1 TB</li>
    </ul>
  </li>
  <li><strong>Planned Upgrade:</strong> 4-bay 2.5" SSD caddy (replacing the DVD drive)</li>
</ul>

<h3>Containers and Applications:</h3>
<ul>
  <li><strong>Plex</strong>: For media streaming and management.</li>
  <li><strong>Sonarr</strong>: Automating TV show downloads.</li>
  <li><strong>Radarr</strong>: Automating movie downloads.</li>
  <li><strong>Lidarr</strong>: Managing and downloading music.</li>
  <li><strong>Soulseek</strong>: For peer-to-peer file sharing.</li>
  <li><strong>SABnzbd & NZBGet</strong>: Usenet downloaders for handling automated media downloads.</li>
  <li><strong>Duplicatip</strong>: For secure cloud backup of important data.</li>
</ul>

<h3>Plugins:</h3>
<ul>
  <li><strong>Unassigned Devices</strong>: For managing drives not assigned to the array.</li>
  <li><strong>Unassigned Devices Preclear</strong>: For preclearing drives before adding them to the array.</li>
  <li><strong>Dynamix File Manager</strong>: For managing files and directories on the server.</li>
</ul>

<p>This setup offers a comprehensive solution for managing and consuming my media collection, with automated tools ensuring everything stays organized and up to date. Future upgrades will enhance storage capacity and flexibility.</p>

<h2>Skills Required for Unraid Server Setup</h2>

<p>Setting up and managing an Unraid server involves a range of skills and knowledge. Here's a breakdown of the key skills required:</p>

<h3>1. Basic Hardware Knowledge</h3>
<ul>
  <li><strong>Understanding of Computer Components:</strong> Knowledge about different hardware components like CPUs, RAM, HDDs, SSDs, and their installation.</li>
  <li><strong>Drive Configuration:</strong> Ability to handle mismatched drives and understand their impact on storage performance and data management.</li>
</ul>

<h3>2. Operating System and Software Management</h3>
<ul>
  <li><strong>Linux Basics:</strong> Familiarity with Linux command line for managing the Unraid server, as Unraid is based on a Linux kernel.</li>
  <li><strong>Unraid OS:</strong> Understanding of Unraid’s web interface for managing disks, shares, and settings.</li>
</ul>

<h3>3. Networking</h3>
<ul>
  <li><strong>Basic Networking Concepts:</strong> Knowledge of IP addressing, network configuration, and troubleshooting.</li>
  <li><strong>Port Forwarding and Firewall Rules:</strong> Ability to configure these settings for remote access to applications like Plex.</li>
</ul>

<h3>4. Docker and Container Management</h3>
<ul>
  <li><strong>Docker Basics:</strong> Understanding how to set up, configure, and manage Docker containers.</li>
  <li><strong>Container Configuration:</strong> Knowledge of configuring containers for specific applications, including network settings and data volume management.</li>
</ul>

<h3>5. Application Configuration</h3>
<ul>
  <li><strong>Media Applications:</strong> Familiarity with configuring media management tools like Plex, Sonarr, Radarr, Lidarr, and how they interact with each other.</li>
  <li><strong>Usenet Downloaders:</strong> Knowledge of setting up and configuring SABnzbd and NZBGet for automated downloads.</li>
</ul>

<h3>6. Backup and Data Protection</h3>
<ul>
  <li><strong>Backup Strategies:</strong> Understanding of how to set up and manage backups, including using services like Backblaze for cloud backup.</li>
  <li><strong>Data Recovery:</strong> Basic skills in recovering data from different 
