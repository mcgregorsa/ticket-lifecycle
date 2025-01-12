![agent-john-works-ticket](https://github.com/user-attachments/assets/c197cf80-29ca-4914-a4fe-f8c8c4e607a1)<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

# <h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>

This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket and follows directly from the tutorial on [osTicket: Post-installation Configuration](https://github.com/mcgregorsa/post-install-config).
<br />



## <h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

## <h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

## <h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

## <h2>Ticket Lifecycle Examples</h2>

<p>Note: Tickets are created in a variety of ways (phone, chat app, email, web portal). In the following examples only the osTicket web portal is being used.</p>

### <h3>Ticket 1: Online Banking System Down</h3>

- Sign in as a User Karen Tyrell on the osTicket Support Center site ans click "Open a New Ticket".
  - Select the Help Topic as "Report a Problem".
  - Fill in the "Issue Summary" formfield and a description in the textfield below it per the image.

<p>
<img src="https://github.com/user-attachments/assets/d6f95e59-9fcb-43a0-a294-71c77ce96965" height="80%" width="80%" alt="Open New Ticket"/>
</p>
<br />

- Sign in as Agent John Smith to triage the ticket.
  - Observe the following ticket properties:
    - Priority, Department, SLA, Assigned To, and Help Topic
  - Set the Properties of the ticket to:
    - Priority: Emergancy
    - SLA Plan: Sev-A
    - Help Topic: Report a Problem/Business Critical Outage
    - Assigned To: Online Banking
    - See the images for examples and note the reply thread as it updates.
      - Use Post Reply throughout the various steps to update actions taken while working tickets.
        - When posting replies the user will receive an email copy that they can respond to.

<p>
<img src="https://github.com/user-attachments/assets/73d01257-28e3-49fd-a477-764b1695ca47" height="80%" width="80%" alt="Agent John Triage Ticket"/>
</p>
<br />

- Sign in as Agent Jane Doe to work the ticket to completion.
  - Select the ticket and assign it to Jane Doe.
  - See images for examples and note the threaded replies.
  - Fill out the fields per the image examples and set the ticket to resolved.
    - You can view resolved/closed tickets from the Closed dropdown under the Tickets Tab.

<p>
<img src="https://github.com/user-attachments/assets/5ac69239-85a4-432a-906e-bda5a4681d9b" height="80%" width="80%" alt="Agent Jane Works Ticket"/>
</p>
<br />

### <h3>Ticket 2: Accounting Department Adobe Upgrade</h3>

- Sign in as a User Karen Tyrell on the osTicket Support Center site ans click "Open a New Ticket".
  - Select the Help Topic as "General Inquiry/Other".
  - Fill in the "Issue Summary" formfield and a description in the textfield below it per the image.

<p>
<img src="https://github.com/user-attachments/assets/ab160f41-caa9-4e4d-b030-9066891e5334" height="80%" width="80%" alt="Open New Ticket--Adobe Issue"/>
</p>
<br />

- As Agent John Smith:
  - Observe and set the ticket properties.
    - SLA Plan: Sev-C
    - Assigned To: John Smith
  - Work the ticket to completion per the images.

<p>
<img src="https://github.com/user-attachments/assets/85355512-6562-4812-a99e-a181847a93a6" height="80%" width="80%" alt="Agent John Works Adobe Ticket"/>
</p>
<br />

### <h3>Ticket 3: CFO's Laptop won't turn on</h3>

- Sign in as a User Karen Tyrell on the osTicket Support Center site ans click "Open a New Ticket".
  - Select the Help Topic as "Repot a Problem/Personal Computer Issues".
  - Fill in the "Issue Summary" formfield and a description in the textfield below it per the image.

<p>
<img src="https://github.com/user-attachments/assets/0076ba17-d03b-458e-95eb-db686f2e42b0" height="80%" width="80%" alt="Open CFO Ticket"/>
</p>
<br />

- As Help Desk Agent John Smith:
  - Observe and set the ticket properties.
    - Priority: Emergency
    - SLA Plan: Sev-B
    - Assigned To: John Smith
  - Work the ticket to completion per the images.

<p>
<img src="https://github.com/user-attachments/assets/82af046d-bfc0-4f84-ac8d-f06076edd374" height="80%" width="80%" alt="Agent John Works CFO Ticket"/>
</p>
<br />
