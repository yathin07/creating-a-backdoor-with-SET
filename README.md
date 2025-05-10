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

![image](https://github.com/user-attachments/assets/8f011fda-01d8-44b9-8d1a-f30598e3ed9a)


### The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

## OUTPUT :

![image](https://github.com/user-attachments/assets/942b58d5-72ba-4ed7-a08b-abf1a132902f)


### It displays the following menu and select 2 for Website Attack Vectors:

## OUTPUT :




### The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

## OUTPUT :

![image](https://github.com/user-attachments/assets/6b3e3947-4d48-430a-a8f9-28e7e22fcf1d)


### The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

## OUTPUT :

![image](https://github.com/user-attachments/assets/3d729e8f-6837-4f4e-b36b-9ccc01ec0fb6)


### It shows the following screen in which the ip address of the attacker need to be given which is the default value:

## OUTPUT :



### It shows the following screen in which the option Google can be selected:

## OUTPUT :

![image](https://github.com/user-attachments/assets/2d7ed8e5-ace6-4ad1-9974-f363e1ca91aa)


### SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

## OUTPUT :

![image](https://github.com/user-attachments/assets/2f6795e5-92d5-46e9-9a12-c3d6ad5d61e4)


### In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

## OUTPUT :

![image](https://github.com/user-attachments/assets/779102c3-6dab-4c88-9c11-0b3bd0b3e9d3)



### SET logs the information regarding the Google credentials:
## OUTPUT :
![image](https://github.com/user-attachments/assets/1a39e0e0-8f21-48c5-b63b-e8b2e846612c)


### SET logs the information in the xml file under /root/.set directory:

![image](https://github.com/user-attachments/assets/658c3592-bb49-4541-a8c9-c214dd313a15)


## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
