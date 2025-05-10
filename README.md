# creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode


### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. 
![image](https://github.com/user-attachments/assets/928f23f4-0965-46e6-b7dd-302fa4a58569)

The command sudo setoolkit in the prompt gives menu with set prompt:
![image](https://github.com/user-attachments/assets/fd3652c1-9eea-439c-bb9b-d03bf2b5545d)

It displays the following menu and select 2 for Website Attack Vectors:
![image](https://github.com/user-attachments/assets/af33d9f1-744c-45ca-ad21-a514b4a14879)
The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:
![image](https://github.com/user-attachments/assets/15cb2543-4dc7-41e2-9109-4ba156501208)
The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected: 
![image](https://github.com/user-attachments/assets/4fdaddde-07c7-4f2e-9cbf-322c5c671063)
It shows the following screen in which the ip address of the attacker need to be given which is the default value:
![image](https://github.com/user-attachments/assets/65a55cd7-bdd7-4d30-96fc-2189b8564404)
In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password
![image](https://github.com/user-attachments/assets/debf04c0-791c-49dd-9057-d3cbe7d223e4)
SET logs the information in the xml file under /root/.set directory:
![image](https://github.com/user-attachments/assets/b006139b-a863-4791-845e-a840260b023c)

## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
