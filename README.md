<!-- osTicket Logo -->
<p align="center">
  <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo">
</p>

<!-- Heading -->
<h1 align="center">osTicket - Post-Install Configurations</h1>

<!-- Environments and Technologies Used -->
<h2 align="center">Environments and Technologies Used</h2>

<p align="center">
  - Microsoft Azure (Virtual Machines/Compute)<br>
  - Remote Desktop Connection<br>
  - osTicket
</p>

<!-- Operating Systems Used -->
<h2 align="center">Operating Systems Used</h2>

<p align="center"><b>- Windows 10 Pro (22H2)</b></p>

<!-- Configuration Steps -->
<h2 align="center">Configuration Steps</h2>

<!-- Images in the following steps are center-aligned -->
<p align="center">
  <img src="https://i.imgur.com/gQJICtM.png" height="80%" width="80%" alt="Configuration Steps">
  <img src="https://i.imgur.com/u7bLxp0.png" height="80%" width="80%" alt="Configuration Steps">
</p>

After installing osTicket, it is now time to make configurations to use it as a ticketing system. One thing to note is that I switch between Admin and Agent panels as each panel has different configurations. To tell which panel is used, look at the top right of the osTicket screen. If it reads Agent Panel, the Admin panel is the one being used and vice versa.

1. **Create Supreme Admin Role:**
   - Open the Admin panel, go to the Agents Menu, and click on Roles to create a new role called Supreme Admin.

<p align="center">
  <img src="https://i.imgur.com/qvyENL6.png" height="80%" width="80%" alt="Configuration Steps">
</p>

2. **Create System Administrators Department:**
   - In the Admin panel, open the Agents menu, and click on Departments to create a new Department within osTicket.

<p align="center">
  <img src="https://i.imgur.com/V5QAtdg.png" height="80%" width="80%" alt="Configuration Steps">
</p>

3. **Create Level II Support Team:**
   - Enter the Admin panel, open the Agents menu, click on Teams, and add any new teams that need to be created.

<p align="center">
  <img src="https://i.imgur.com/wnhpEZL.png" height="80%" width="80%" alt="Configuration Steps">
  <img src="https://i.imgur.com/32jwdVC.png" height="80%" width="80%" alt="Configuration Steps">
</p>

4. **Create New Agents:**
   - Enter the Admin panel, open the Agents menu, click on Add New Agent, and create the account credentials for each new agent.

<p align="center">
  <img src="https://i.imgur.com/Y2nXl7Q.png" height="80%" width="80%" alt="Configuration Steps">
</p>

5. **Create New Users:**
   - Enter the Agents panel, open the Users menu, click on Add User, and create the account credentials for each new user.

<p align="center">
  <img src="https://i.imgur.com/brPLjiI.png" height="80%" width="80%" alt="Configuration Steps">
</p>

6. **Define SLAs (Service Level Agreements):**
   - Enter the Admin panel, open the Manage menu, click on SLA, and create any needed SLAs.

<p align="center">
  <img src="https://i.imgur.com/u5HZAyP.png" height="80%" width="80%" alt="Configuration Steps">
</p>

7. **Create Help Topics:**
   - Enter the Admin panel, open the Manage menu, click on Help Topics, and click on Add New Help Topic.

<h2 align="center">osTicket Configurations are Complete</h2>

Now that the configurations have been set in place, you can utilize osTicket as a proper ticketing system. You can create tickets and allocate them as if you were in a real environment.
