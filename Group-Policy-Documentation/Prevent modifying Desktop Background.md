## Prevent modifying Desktop Background
<br>

On the Group *Policy Management Editor*, navigate to *User Configuration*>*Policies*>*Administrative Tools*>*Control Panel*>*Personalization*>*Prevent changing desktop background*.
<br>

![image](https://github.com/user-attachments/assets/baa7527b-6f1c-493a-876e-de0708697fc1)
<br>

Enable the policy. Click on **Apply** then **OK**.
<br>

![image](https://github.com/user-attachments/assets/328a4766-0f08-4082-b971-3520cb4d5dbb)

<br>

Login on the client/user side. open [cmd](https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/cmd) and type ```gpupdate```. Once done, logout or signout on the computer. This is one of the ways to manually refresh Group Policy on the local computer. 
<br>

When Group Policy is refreshed, if certificate autoenrollment is configured and functioning correctly, the local computer is autoenrolled a certificate by the certification authority (CA).
<br>

## Reference
 * [Prevent Users changing Desktop Wallpaper with Group Policy](https://www.petenetlive.com/KB/Article/0000461)
 * [Refresh Group Policy](https://learn.microsoft.com/en-us/windows-server/networking/core-network-guide/cncg/server-certs/refresh-group-policy)
   

