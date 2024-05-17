# GrabThePhisher Blue Team Lab

### Scenario:

An attacker compromised a server and impersonated https://pancakeswap.finance/, a decentralized exchange native to BNB Chain, to host a phishing kit at https://apankewk.soup.xyz/mainpage.php. The attacker set it as an open directory with the file name "pankewk.zip". 

Provided the phishing kit, you as a soc analyst are requested to analyze it and do your threat intel homework.


#### 1. Download the challenge file and unzip it:

<img width="596" alt="Screen Shot 2024-05-16 at 4 58 45 PM" src="https://github.com/zerothegreat1/CyberDefenders/assets/164509453/13ee1cda-dd05-49b9-8c97-a4c2ea947cc7">

- Which wallet was used for asking the seed phrase?
m*******

#### 2. Browse to c75-GrabThePhisher > pankewk > metamask
<img width="595" alt="Screen Shot 2024-05-16 at 4 59 29 PM" src="https://github.com/zerothegreat1/CyberDefenders/assets/164509453/cfc47191-4466-4992-9f4e-8e1eee87e5e0">

#### 3. Open the file metamask.php with your choice of text editor/viewer

<img width="1013" alt="Screen Shot 2024-05-16 at 6 42 47 PM" src="https://github.com/zerothegreat1/CyberDefenders/assets/164509453/534c6183-afc7-490c-bf4a-94214b4e6889">

- What is the file name that has the code for the phishing kit?
m*******.***

- In which language was the kit written?
p**

<img width="602" alt="Screen Shot 2024-05-16 at 5 00 01 PM" src="https://github.com/zerothegreat1/CyberDefenders/assets/164509453/5e89d972-7a47-4602-926b-698648121fe6">

- What service does the kit use to retrieve the victim’s machine information?
s**** ***
<img width="602" alt="Screen Shot 2024-05-16 at 5 00 01 PM" src="https://github.com/zerothegreat1/CyberDefenders/assets/164509453/3d295126-9c1a-4348-8eb4-30f2ab8a01d1">

#### 4. Browse to c75-GrabThePhisher > pankewk > log
- Open log.txt

<img width="603" alt="Screen Shot 2024-05-16 at 5 01 13 PM" src="https://github.com/zerothegreat1/CyberDefenders/assets/164509453/1ac09e8c-2577-4388-a38c-30bcafdb379e">

- How many seed phrases were already collected? *
  
- Write down the seed phrase of the most recent phishing incident?
f***** **** ******* ****** ******* ******* ******** ******* ***** **** ****** ******


#### 5. Look inside the file metamask.php again

<img width="598" alt="Screen Shot 2024-05-16 at 5 00 38 PM" src="https://github.com/zerothegreat1/CyberDefenders/assets/164509453/b987849f-b05f-439a-9afd-0b0bdfe2dc54">

- Which medium had been used for credential dumping?
t*******

- What is the token for the channel?
5*********:***********************************
  
<img width="598" alt="Screen Shot 2024-05-16 at 5 00 38 PM" src="https://github.com/zerothegreat1/CyberDefenders/assets/164509453/28547a24-41e8-47cc-9a0e-8f4a918ee93c">

- What is the chat ID of the phisher’s channel?
5*********

#### To find the full name of the phish actor, we have to use the information that we have on-hand like the Telegram userID, token, and url found inside the file metamask.php
Read about the Telegram bot API from the page, https://core.telegram.org/bots/api#getchatmember
We will have to utilize the sendMessage method in Telegram, passing the chatID and sending a random message through text.
Enter the following to the URL bar: https://api.telegram.org/botenter_token_here/sendMessage?chat_ID= enter_userID_here&text=Hello_World

<img width="599" alt="Screen Shot 2024-05-16 at 5 02 31 PM" src="https://github.com/zerothegreat1/CyberDefenders/assets/164509453/b971e957-4ad5-41f1-af66-e1251cb850d5">

- What is the alias of the phish kit developer?
j***********

- What is the full name of the phish actor?
M***** ********

- What is the username of the phish actor?
p**********
