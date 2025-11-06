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
The command sudo setoolkit in the prompt gives menu with set prompt:
## OUTPUT


<img width="891" height="621" alt="image" src="https://github.com/user-attachments/assets/6be32a68-24b4-4de1-81af-9c6837782016" />



The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
## OUTPUT

<img width="420" height="239" alt="image" src="https://github.com/user-attachments/assets/a1c33b7d-c3a6-41a0-8813-d24c6cd58008" />


It displays the following menu and select 2 for Website Attack Vectors:
## OUTPUT

<img width="463" height="275" alt="image" src="https://github.com/user-attachments/assets/d4375c65-250a-4892-8c7a-e2be94a13f61" />

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:
## OUTPUT
<img width="472" height="208" alt="image" src="https://github.com/user-attachments/assets/957c83ad-5adc-41f0-b860-35cac9088211" />


The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
## OUTPUT

<img width="290" height="129" alt="image" src="https://github.com/user-attachments/assets/d9b2108b-9763-4fc5-a886-9ce84c2a334c" />


It shows the following screen in which the ip address of the attacker need to be given which is the default value:
## OUTPUT

<img width="715" height="380" alt="image" src="https://github.com/user-attachments/assets/932ce89b-37d6-4c16-89eb-79e12a8f8cfa" />



It shows the following screen in which the option Google can be selected:
## OUTPUT


<img width="709" height="424" alt="image" src="https://github.com/user-attachments/assets/06869083-25ae-4c95-9887-445035a8bec5" />



SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
## OUTPUT

<img width="935" height="196" alt="image" src="https://github.com/user-attachments/assets/cc745955-48fc-420d-b13c-53bad993a9ca" />



In windows IE, on giving the url http://192.168.1.2 (use appropriate IP address), the fake Google page is displayed. The victim can enter the username and password
## OUTPUT

<img width="547" height="898" alt="image" src="https://github.com/user-attachments/assets/953b2b04-a658-451b-aa88-2ab3f941dc7d" />

SET logs the information regarding the Google credentials:
## OUTPUT

<img width="823" height="140" alt="image" src="https://github.com/user-attachments/assets/3c4e1d0e-c5cd-4b7f-8b86-69c741e9f741" />


SET logs the information in the xml file under /root/.set directory:
## OUTPUT

<img width="827" height="428" alt="image" src="https://github.com/user-attachments/assets/0cd175aa-e854-4aa5-b4f5-064814f053af" />











## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
