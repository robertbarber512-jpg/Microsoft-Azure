<p align="center">
<img <img width="275" height="183" alt="download" src="https://github.com/user-attachments/assets/f54141d0-84a4-49a1-8bfd-0154f6324457" />
 
</p>

<h1>Connecting to a Virtual Machine Using Remote Desktop</h1>
This tutorial outlines the implementation of a remote desktop connection within Azure Virtual Machines.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (22H2)



<h2>Deployment and Configuration Steps</h2>

<p>
<img /><img width="1920" height="1080" alt="Screenshot (88)" src="https://github.com/user-attachments/assets/4c029740-e637-4a39-a8a9-cef2e678628b" />

</p>
<p>
<p>
Start by making a resource group for the virtual machine in azure. Does not matter which region you select just make note as the virtual machine must have the same one. Ended up changing the region to Canada later.
</p>
<br />

<p>
<img <img width="1920" height="1080" alt="Screenshot (90)" src="https://github.com/user-attachments/assets/7965dcc7-1129-4158-83b4-7eafe7521cae" />

</p>
<p>
Next we will create the virtual machine and put it in the resource group we made.</p>


<p>
<img/>
</p><img width="1920" height="1080" alt="Screenshot (91)" src="https://github.com/user-attachments/assets/2ba141bc-e41b-403a-aeaa-eb6691236624" />

<p><img width="1920" height="1080" alt="Screenshot (92)" src="https://github.com/user-attachments/assets/dbb4cb3d-ba45-42c1-8479-d9d49a03d480" />
</p>
You will have to make a username and password choose what you would like and make note of it you will need it later.With those preferences inputed go ahead and create the virtual machine.
</p>
<br />

</p><img width="1920" height="1080" alt="Screenshot (94)" src="https://github.com/user-attachments/assets/10ce73d9-8400-459a-9614-a9cb6bbe5e4a" />
</p>
Once completed we will select the virtual machine and find the public ip address
</p>
<br />
<br />


<img width="1920" height="1080" alt="Screenshot (95)" src="https://github.com/user-attachments/assets/4c4bd9bb-71fd-49a0-a217-fb77c0cca71d" />


<img width="1920" height="1080" alt="Screenshot (96)" src="https://github.com/user-attachments/assets/9f8ba549-1899-4667-9121-b775864b34c5" />
<br />
</p>
From the start or search bar look up remote desktop and open
</p>

<br />
<img width="1920" height="1080" alt="Screenshot (97)" src="https://github.com/user-attachments/assets/5e824ad5-ea4f-459e-956e-ca04ea2eedba" />
</p>
Input the ip address from the virual machine. It will then ask for the username and password, once those are entered connect.
</p>

<img width="1920" height="1080" alt="Screenshot (98)" src="https://github.com/user-attachments/assets/e9f6f98a-cc90-4361-9147-59ecf0d7e82f" />


<br />
