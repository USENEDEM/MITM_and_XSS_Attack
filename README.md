# MITM_and_XSS_Attack

### Preview 
___

This is a life simulation of network attack to check network vulnerability using man-in-the-middle(MITM) attack and checking web application vulnerability using cross-site(XSS) scripting attack.

Skills (*Learned*) 
___

1. Network vulnerability assessment
2. Web application testing
3. proxy integration

 ### Tools 
 ___

 1. Burpsuite community edition -MITM attack
 2. XSSER -cross site scripting attack
 3. Proxy

### Procedures 
___

1. XSSER - I installed XSSER using the command

```zsh
sudo apt install xxser
```

Ran a simple XSS attack command

```zsh
sudo xsser -u 'domain name' -g 'list product.php?cat=xss
```


<img width="1280" alt="Screenshot 2024-06-13 at 22 35 42" src="https://github.com/USENEDEM/MITM_and_XSS_Attack/assets/169564406/65c798e8-be19-4e46-8a5f-5bc23c8ac3b4">



<img width="1280" alt="Screenshot 2024-06-13 at 23 07 30" src="https://github.com/USENEDEM/MITM_and_XSS_Attack/assets/169564406/7b669843-bda3-469f-9516-fee6c1b75d52">


*Ref.* 1 (XSSER installation) *Ref.* 2 (XSS attack using XSSER)

2. Burpsuite - I installed burpsuite community edition on my kali linux
   - Setup my foxy-proxy with my burpsuite ip and port number.
   - Started up my foxy-proxy and burpsuite, i set the intercepion on my burpsuite to 'on'. This is to enable interception between my browser and internet web applications. Burpsuite also gives the privilage of intercepting and temparing/altering (inserting commands/text/strings) before forwarding the request to the web application.
  


<img width="1280" alt="Screenshot 2024-06-12 at 11 54 08" src="https://github.com/USENEDEM/MITM_and_XSS_Attack/assets/169564406/b50587c1-c41b-47f7-a9f4-20c63aacd02d">


*Ref 3* (setting up foxy-proxy using burpsuite *ip* dn *port number* )



<img width="1280" alt="Screenshot 2024-06-12 at 16 29 56" src="https://github.com/USENEDEM/MITM_and_XSS_Attack/assets/169564406/f234f42a-da04-43e0-aca3-48d5158a2859">



<img width="1280" alt="Screenshot 2024-06-13 at 09 31 30" src="https://github.com/USENEDEM/MITM_and_XSS_Attack/assets/169564406/8032cea2-13a9-4a80-afff-9fbe1adfc6f6">



<img width="1280" alt="Screenshot 2024-06-13 at 09 38 59" src="https://github.com/USENEDEM/MITM_and_XSS_Attack/assets/169564406/55e4ce45-b198-4de3-89f6-16e721da2bec">



<img width="1280" alt="Screenshot 2024-06-13 at 09 42 25" src="https://github.com/USENEDEM/MITM_and_XSS_Attack/assets/169564406/22eb2ac6-201e-48a8-834e-f5e27db4112c">

*Ref 4,5,6,7* (Burpsuite interceptions and log list).







   
