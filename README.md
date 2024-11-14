<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />






<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Item 1, Configure Roles (for grouping permissions)
Navigate to Admin Panel -> Agents -> Roles
Create and configure roles, such as Supreme Admin, with permissions for full access to system features. 
- Item 2, Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
Navigate to Admin Panel -> Agents -> Departments
Set up department structures, for example, create SysAdmins to handle tickets related to system administration.
- Item 3, Configure Teams (Pull Agents from different Departments)
Navigate to Admin Panel -> Agents -> Teams
Set up teams such as Online Banking by pulling agents from multiple departments, such as Support and SysAdmins.
- Item 4, Allow Anyone to Create Tickets
Navigate to Admin Panel -> Settings -> User Settings
UNcheck the option to allow unregistered users to create tickets. Require registration and login for users to create tickets.
- Item 5, Configure SLA (Service Level Agreements)
Navigate to Admin Panel -> Manage -> SLA
Define different SLA levels, for example:
Sev-A with a grace period of 1 hour, 24/7 schedule.
Sev-B with a grace period of 4 hours, 24/7 schedule.
Sev-C with a grace period of 8 hours, business hours schedule.

<h2>Configuration Steps</h2>

<p>
<img src=https://i.imgur.com/wzeun5p.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
This screenshot demonstrates the osTicket post-installation setup, showcasing both the admin panel configuration and the client portal. It highlights how to configure user roles, departments, and teams to manage ticket visibility and agent permissions. Additionally, it shows the client portal where users can submit tickets. This image illustrates the configuration process for roles, allowing admins to assign permissions and set up efficient workflows for managing support requests.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
