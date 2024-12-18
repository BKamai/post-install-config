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

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Users
- Configure SLA
- Configure Help Section

<h2>Roles</h2>
    <ul>
      <li>Navigate to: Admin Panel -> Agents -> Roles</li>
      <li>Assign the "Supreme Admin" role for full administrative control.</li>
    </ul>
    <p>
      <img src="https://i.imgur.com/mgscpJs.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
    </p>
  <p>
    <img src="https://i.imgur.com/OKc53SA.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
  </p>
  </li>

  
<h2>Departments</h2>
    <ul>
      <li>Navigate to: Admin Panel -> Agents -> Departments</li>
      <li>Create a department called "System Administrators" to handle high-priority system-level issues.</li>
    </ul>
  <p>
    <img src="https://i.imgur.com/DaPRt5N.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
  </p>
  </li>

  
<h2>Teams</h2>
    <ul>
      <li>Navigate to: Admin Panel -> Agents -> Teams</li>
      <li>Set up a Level II support team to handle support requests.</li>
    </ul>
    <p>
      <img src="https://i.imgur.com/xqzuyHJ.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
    </p>
  </li>
  
<h2>Agents</h2>
    <ul>
      <li>Navigate to: Admin Panel -> Agents -> Add New</li>
      <li>Create a user named Jane Doe.</li>
    </ul>
    <p>
      <img src="https://i.imgur.com/XCwcHEg.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
    </p>
    <ul>
      <li>Select Set Password.</li>
      <li>Uncheck the "Send the agent a password reset email" and "Require password change at next login" options.</li>
      <li>Provide agent Jane Doe a new password.</li>
    </ul>
    <p>
    <img src="https://i.imgur.com/frUDcpu.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
    </p>
    <ul>
      <li>Select the Access Tab.</li>
      <li>Assign Jane Doe to 'System Administrator' and 'Supreme Admin' roles.</li>
    </ul>
    <p>
    <img src="https://i.imgur.com/Y7FKY2i.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
    </p>
    <ul>
      <li>Now select the Teams Tab.</li>
      <li>Assign Jane Doe to 'Level II Support'.</li>
    </ul>
    <p>
    <img src="https://i.imgur.com/lFCUVub.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
    </p>
    <ul>
      <li>Complete this process once again for an agent named 'John Doe'.</li>
      <li>However, within the Access tab, assign John Doe the 'Support' Department.</li>
    </ul>
    <p>
    <img src="https://i.imgur.com/wJJua6h.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
    </p>
    <p>
    <img src="https://i.imgur.com/tXHvRoM.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
    </p>
  </li>

  
<h2>Users</h2>
    <ul>
      <li>Navigate to: Agent Panel -> Users -> Add New</li>
      <li>Add users like "Karen Karen" and "Ken Ken" who will submit tickets for support.</li>
    </ul>
    <p>
    <img src="https://i.imgur.com/TfBRo1K.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
    </p>
  </li>

  
<h2>SLAs</h2>
    <p>SLAs define the timeframes within which tickets should be resolved based on their severity. Proper configuration of SLAs ensures critical issues are prioritized and handled efficiently.</p>
    <ul>
      <li>Navigate to: Admin Panel -> Manage -> SLA</li>
      <li>Set up the following SLAs:
        <ul>
          <li><strong>Sev-A:</strong> 1 hour, 24/7 coverage for critical system outages.</li>
          <p>
            <img src="https://i.imgur.com/w1Oto4S.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
          </p>
          <li><strong>Sev-B:</strong> 4 hours, 24/7 coverage for high-priority issues like software failures.</li>
          <p>
            <img src="https://i.imgur.com/NiY7vIt.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
          </p>
          <li><strong>Sev-C:</strong> 8 hours, business hours coverage for less critical issues, such as password resets.</li>
          <p>
            <img src="https://i.imgur.com/eSfiv2C.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
          </p>
        </ul>
      </li>
    </ul>
  </li>

  
<h2>Help Topics</h2>
    <p>Help topics categorize the types of support requests users may submit. Proper categorization helps route tickets to the correct team or department.</p>
    <ul>
      <li>Navigate to: Admin Panel -> Manage -> Help Topics</li>
      <li>Add a help topic:
        <ul>
          <li>Password Reset</li>
          <p>
            <img src="https://i.imgur.com/rDCbHjA.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
          </p>
        </ul>
      </li>
    </ul>
  </li>
</ul>
