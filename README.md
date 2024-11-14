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
<img src=https://i.imgur.com/vcgHYv2.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
These images showcase the osTicket post-installation process, highlighting key configuration steps. It demonstrates how to configure teams by pulling agents from different departments, such as creating an Online Banking team. It also shows how to enforce registration requirements by unchecking the option that allows unregistered users to create tickets, ensuring users must log in before submitting tickets. The image further illustrates how to configure agents (e.g., Jane in SysAdmins and John in Support) and add customer users (e.g., Karen and Ken) to enable them to submit and track their tickets. These steps are essential for structuring your ticketing system and streamlining user and agent management.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Finally, this screenshot illustrates the configuration of Service Level Agreements (SLAs) and Help Topics within osTicket. It shows how to define SLAs with different grace periods and schedules, such as Sev-A (1 hour grace period, 24/7 schedule), Sev-B (4 hours grace period, 24/7 schedule), and Sev-C (8 hours grace period, business hours). Additionally, it demonstrates setting up Help Topics that users can select when submitting tickets, such as Business Critical Outage, Personal Computer Issues, Equipment Request, Password Reset, and Other. These configurations help streamline ticket management and categorize incoming requests for better resolution handling.
</p>
<br />
