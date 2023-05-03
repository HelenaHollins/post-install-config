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

- Roles
- Departments
- Teams
- Agents
- Users
- SLA
- Help Topics

<h2>Configuration Steps</h2>

<p>
<br />
  <br />
1. Configure Roles
  <p>
    
- Admin Panel -> Agents -> Roles
    ->Add new role
    
- Give your new role all access
    
- Create role (All Access Admin)   
</p>
<p>
  
![image](https://user-images.githubusercontent.com/42724831/235966436-d47265af-d964-4ba2-aaa6-d54d747d9d24.png)

</p>
<br />

<p>
<br />
  <br />
2. Configure Departments
  <p>
    
- Admin Panel -> Agents -> Departments
    ->Add new department
      
- Create department (Systems Administrators)    
</p>
<p>
  
![image](https://user-images.githubusercontent.com/42724831/235968203-f19f799e-9fa1-4d1d-bd03-faa6aa741345.png)


</p>
<br />

<p>
<br />
  <br />
3. Configure Teams
  <p>
    
- Admin Panel -> Agents -> Teams
    ->Add new team
    
- Create a new team (Level II Support)    
         
</p>
<p>
  
![image](https://user-images.githubusercontent.com/42724831/235977984-2efe954f-af4c-49b1-bc17-def446273efb.png)  


</p>
<br />

<p>
<br />
  <br />
4. Allow anyone to create tickets
  <p>
    
- Admin Panel -> Settings -> User Settings
    
- Make sure 'Require registration and login to create tickets' is unchecked
         
</p>
<p>
  
![image](https://user-images.githubusercontent.com/42724831/235975262-5eba5e15-5bfc-47cb-88f2-f22d921fd3ef.png)  


</p>
<br />

<p>
<br />
  <br />
5. Configure Agents
  <p>
    
- Admin Panel -> Agents -> Add New
    
- Create agent (Jane Doe)
    
- Create agent (John Doe)    
         
</p>
<p>
  
  ![image](https://user-images.githubusercontent.com/42724831/235979624-f17325ca-5e30-4ffb-afc7-52a5bc5bba83.png)  

</p>
<br />

<p>
<br />
  <br />
6. Configure Users
  <p>
    
- Agent Panel -> Users -> Add New
    
- Create user (Karen Hill)
    
- Create user (Jack Williams)
    
- Create user (Sarah Bell)    
         
</p>
<p>
  
  ![image](https://user-images.githubusercontent.com/42724831/235981200-0ace58c8-5815-4eb1-98b9-953e71fee06b.png)  

</p>
<br />

<p>
<br />
  <br />
7. Configure SLA
  <p>
    
- Admin Panel -> Manage -> SLA
    ->Add new SLA Plan
    
- Create Sev-A (1 hour, 24/7)
    
- Create Sev-B (4 hours, 24/7)
    
- Create Sev-C (8 hours, business hours)    
         
</p>
<p>
  
  ![image](https://user-images.githubusercontent.com/42724831/235982635-05617762-6673-465a-b5c6-c4bcb4d7d14c.png)  

</p>
<br />

<p>
<br />
  <br />
8. Configure Help Topics
  <p>
    
- Admin Panel -> Manage -> Help Topics
    ->Add new Help Topic
    
- Create new topic (Critical Outage)
    
- Create new topic (Equipment Request)
    
- Create new topic (Password Reset)    
         
</p>
<p>
  
  ![image](https://user-images.githubusercontent.com/42724831/235984362-911cefe4-1617-4e0e-9fe4-6f2c35c4c52f.png)  

</p>
<br />
