### [5. Configuració xarxa bàsica]

El primer pas és accedir a la configuració de xarxa d'una màquina  
![01](images/xarxa/Screenshot_1.png)  
Després, afegirem manual i ho canviarem  
![02](images/xarxa/Screenshot_2.png)  
Veurem amb l'IP a què s'ha canviat i ho farem també amb un altre mode  
![03](images/xarxa/Screenshot_3.png)  
Esborrarem el següent arxiu.  
![04](images/xarxa/Screenshot_4.png)  
Entrarem al directori on està la configuració de la xarxa, farem un `ls` per veure els arxius i obrirem amb un `sudo nano` l'arxiu de configuració  
![05](images/xarxa/xarxxa.png)  
Canviarem els paràmetres per afegir els següents que ens donaran servei  
![06](images/xarxa/Screenshot_5.png)  
Farem un `sudo netplan apply` i veurem com s'ha canviat la IP  
![07](images/xarxa/Screenshot_6.png)  
