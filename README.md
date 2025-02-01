<p align="center">
  <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
<p>
  Hello there! This section of my GitHub documents the outline, prerequisites, and installation of osTicket—an open-source help desk ticketing system. Although there are no videos or screenshots, I hope this comprehensive guide will help you set up your own ticketing software. Enjoy!
</p>

<h2>Project Overview</h2>
<p>
  I set up the osTicket help desk system on a Microsoft Azure Virtual Machine running Windows 10 (21H2), using Internet Information Services (IIS) to host the application. This guide is based on my hands-on experience with cloud deployment, system configuration, and technical documentation. I hope you find it helpful as you set up your own ticketing system!
</p>

<h2>Environments and Technologies Used</h2>
<ul>
  <li>Microsoft Azure (Virtual Machines/Compute)</li>
  <li>Remote Desktop</li>
  <li>Internet Information Services (IIS)</li>
</ul>

<h2>Operating Systems Used</h2>
<ul>
  <li>Windows 10 (21H2)</li>
</ul>

<h2>List of Prerequisites</h2>
<ul>
  <li><strong>Microsoft Azure Virtual Machine (Windows 10 21H2)</strong>: Ensure you have an active Azure account and a provisioned Windows 10 VM with the 21H2 update.</li>
  <li><strong>Internet Information Services (IIS)</strong>: Install and configure IIS on your VM to host the osTicket application.</li>
  <li><strong>PHP Environment</strong>: Install PHP (preferably version 7.4 or later) and enable required extensions such as <code>cURL</code>, <code>GD</code>, <code>IMAP</code>, and <code>mbstring</code>.</li>
  <li><strong>Database Server</strong>: Set up a MySQL or MariaDB instance to manage osTicket’s data storage.</li>
  <li><strong>Remote Desktop Access</strong>: Confirm Remote Desktop is enabled on your VM for easy management and troubleshooting.</li>
</ul>

<h2>Step-by-Step Guide: Prerequisites for osTicket Installation</h2>
<ol>
  <li>
    <strong>Provision Microsoft Azure Virtual Machine</strong>
    <ul>
      <li>Log in to your Microsoft Azure account.</li>
      <li>Create a new Virtual Machine using the Windows 10 (21H2) image.</li>
      <li>Configure the VM size, storage, and networking settings according to your needs.</li>
      <li>Ensure that Remote Desktop is enabled for future management.</li>
    </ul>
  </li>
  <li>
    <strong>Install and Configure Internet Information Services (IIS)</strong>
    <ul>
      <li>Log into your Windows 10 VM.</li>
      <li>Open <em>"Turn Windows features on or off"</em> from the Control Panel.</li>
      <li>Enable <strong>Internet Information Services (IIS)</strong> and complete the installation.</li>
      <li>Verify the installation by opening a browser and navigating to <code>http://localhost</code>.</li>
    </ul>
  </li>
  <li>
    <strong>Set Up the PHP Environment</strong>
    <ul>
      <li>Download PHP (version 7.4 or later) from the official PHP website.</li>
      <li>Install PHP on your VM and configure it to work with IIS (you may use the PHP Manager for IIS for a smoother setup).</li>
      <li>Enable the necessary PHP extensions: <code>cURL</code>, <code>GD</code>, <code>IMAP</code>, and <code>mbstring</code>.</li>
    </ul>
  </li>
  <li>
    <strong>Install the Database Server</strong>
    <ul>
      <li>Download and install MySQL or MariaDB on your VM.</li>
      <li>Create a new database for osTicket.</li>
      <li>Document your database credentials (database name, username, and password) for later configuration.</li>
    </ul>
  </li>
  <li>
    <strong>Verify Remote Desktop Access</strong>
    <ul>
      <li>Ensure that Remote Desktop is enabled on your VM.</li>
      <li>Test connecting from your local machine to verify that the configuration works correctly.</li>
    </ul>
  </li>
</ol>

<h2>Context &amp; Impact</h2>
<p>
  This guide not only showcases my technical skills in deploying a cloud-based IT solution, but it also highlights my ability to create clear, concise documentation. These skills are practical for tackling real-world IT infrastructure and cybersecurity challenges.
</p>

<h2>Technical Insights</h2>
<p>
  During this project, I tackled challenges like ensuring PHP worked seamlessly with IIS and securing remote desktop access. This hands-on experience sharpened my troubleshooting and system optimization skills, and I hope these insights inspire your own projects!
</p>

</body>
</html>
