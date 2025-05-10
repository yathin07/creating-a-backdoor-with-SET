# creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course
## Name: Yathin Reddy T
## Reg No: 212223100062
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

## OUTPUT :

![image](https://github.com/user-attachments/assets/7c21462d-912f-4fcd-be59-57ddd2d66a9b)


### The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

## OUTPUT :

![image](https://github.com/user-attachments/assets/2ab7a916-8ad9-4660-9c3b-9e38a94d3050)


### It displays the following menu and select 2 for Website Attack Vectors:

## OUTPUT :

![image](https://github.com/user-attachments/assets/25be71e6-9939-444a-9891-9e46b643d609)



### The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

## OUTPUT :

![image](https://github.com/user-attachments/assets/78ecdded-343e-48fc-8327-833efa9caed5)


### The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

## OUTPUT :

![image](https://github.com/user-attachments/assets/e96e7977-7cdb-49bb-88a0-43a09f2db8c0)


### It shows the following screen in which the ip address of the attacker need to be given which is the default value:

## OUTPUT :
![image](https://github.com/user-attachments/assets/5caece80-6422-4ac3-8534-a3979e9d01bb)



### It shows the following screen in which the option Google can be selected:

## OUTPUT :

![image](https://github.com/user-attachments/assets/3d053a68-e831-424c-a4f6-f6fc0d7cb70f)


### SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

## OUTPUT :

![image](https://github.com/user-attachments/assets/0b5cd750-802e-4873-8f37-fae3f89334aa)


### In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

## OUTPUT :

![image](https://github.com/user-attachments/assets/b6ea50a4-689b-4d86-89bb-1c7eff714107)



### SET logs the information regarding the Google credentials:
## OUTPUT :
![image](https://github.com/user-attachments/assets/bd7ffd6b-e239-4302-9df5-50c8190c7d0f)


### SET logs the information in the xml file under /root/.set directory:

![image](https://github.com/user-attachments/assets/a07eb861-f334-4a47-830a-21169191d05c)


## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
