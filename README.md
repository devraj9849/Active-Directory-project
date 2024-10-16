<h1>Active-Directory-project</h1>

Active Directory (AD) is a database and set of services that connect users with the network resources they need to get their work done. The database (or directory) contains critical information about your environment, including what users and computers there are and who’s allowed to do what. its purpose is to enable IT departments to create and manage user accounts and control access to resources on corporate networks. With it, admins can create and enforce security policies for the network.

![image](https://github.com/user-attachments/assets/6e0ddebe-b40b-43c0-98fd-f667626a8c97)

<b>Step by Step process for installing Active Directory</b>

First clicking on add roles and Features wizard

![image](https://github.com/user-attachments/assets/0ae9e403-8ce5-4843-ab04-8ba8ea42e17a)

After that selecting role-based installation

![image](https://github.com/user-attachments/assets/f7aa59fe-6770-49e8-b09e-abb83510edcf)


After this it will select a server which is on our system

![image](https://github.com/user-attachments/assets/aba887dd-da40-4d1e-a0d2-ce1234a15eb9)

After this we click on the active directory Domain Services for the active directory.

![image](https://github.com/user-attachments/assets/27b53a6f-f111-4fcf-958b-8e008609ac77)

Installation on Progress

![image](https://github.com/user-attachments/assets/656cf48f-a4d3-4fb6-bf90-a1e785b94d1d)

After the installation is completed it will tell us to Promote this server to Domain controller. When we clicked on it we click on add a new forest option as we do not have a previous domain controller.

![image](https://github.com/user-attachments/assets/698463c4-801d-4ce3-a1d0-982e7e2a7112)

Furthermore we add a password for it which can be seen in the figure below:

![image](https://github.com/user-attachments/assets/daebd8a2-1080-4f32-ad38-41bb43157166)

![image](https://github.com/user-attachments/assets/67744123-ca0f-4957-b8b9-46ea0513b60c)

After all the above process is completed we can review it and install it.

![image](https://github.com/user-attachments/assets/761b4fc6-50e3-4a48-892c-55eee79a1206)

In the middle of the installation the system may restart couple of times.

![image](https://github.com/user-attachments/assets/906b490b-5e86-43b0-8710-a42b51ba203c)


If we have completed all the above steps then we will see the following after restart of the system:

![image](https://github.com/user-attachments/assets/799f42a7-6a99-4667-8c58-7399305fa890)

After this we can create any new user For example BOB and also a group admin user on the active directory. We can see those in the event viewer as:

Event ID: 4720: User account created

![image](https://github.com/user-attachments/assets/ea651df9-a6cd-42d0-b8a4-1a2c6cf8b449)


Event ID: 4726: User account deleted

![image](https://github.com/user-attachments/assets/369a0ad9-cf8b-4713-acff-764231e2f04c)


Event ID: 4727: Creation of security enabled group

![image](https://github.com/user-attachments/assets/69cfb6a9-3c68-49ef-b55e-bf8d23db7431)

So if we have Splunk or any SIEM installed, then we can see all the user that we created, or deleted or any other things that are happening in the system, we can see there or also in Event Viewer.









