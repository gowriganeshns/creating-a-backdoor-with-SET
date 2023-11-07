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

## OUTPUT:
![image](https://github.com/Kirupanandhan/creating-a-backdoor-with-SET/assets/94386222/1f00a8ab-72ac-4321-89fb-ac15f895a946)

The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

## OUTPUT:
![image](https://github.com/Kirupanandhan/creating-a-backdoor-with-SET/assets/94386222/aa82f071-9ca8-4d25-9d12-d2239f14f9f1)

It displays the following menu and select 2 for Website Attack Vectors:

## OUTPUT:
![image](https://github.com/Kirupanandhan/creating-a-backdoor-with-SET/assets/94386222/38fd2691-08b4-4e76-9599-0061728cfd38)


The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

## OUTPUT:
![image](https://github.com/Kirupanandhan/creating-a-backdoor-with-SET/assets/94386222/cee0361c-9f61-4ee4-9357-1aa49e61a598)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

## OUTPUT:
![image](https://github.com/Kirupanandhan/creating-a-backdoor-with-SET/assets/94386222/362616f8-bf73-402c-80c7-1f59d2778754)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:

## OUTPUT:
![image](https://github.com/Kirupanandhan/creating-a-backdoor-with-SET/assets/94386222/ad1ec8f3-3e18-43ea-b520-2673e75400a0)

It shows the following screen in which the option Google can be selected:

## OUTPUT:
![image](https://github.com/Kirupanandhan/creating-a-backdoor-with-SET/assets/94386222/b54b125a-8192-4fd6-ba84-c23a4e1331b6)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

## OUTPUT:
![image](https://github.com/Kirupanandhan/creating-a-backdoor-with-SET/assets/94386222/381f52f9-677f-41e6-879d-f9e14e5063cc)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

## OUTPUT:
![image](https://github.com/Kirupanandhan/creating-a-backdoor-with-SET/assets/94386222/bab281ee-dccc-4511-963b-79b9fd9360bb)

SET logs the information regarding the Google credentials:

## OUTPUT:
![image](https://github.com/Kirupanandhan/creating-a-backdoor-with-SET/assets/94386222/1f91e817-81e3-4ed0-98dd-75145842e812)

SET logs the information in the xml file under /root/.set directory:

## OUTPUT:
![image](https://github.com/Kirupanandhan/creating-a-backdoor-with-SET/assets/94386222/441b35f3-839d-4030-bd35-6f040ddc093b)


















## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
