# Ubuntu Server Apache2
1. Installare openssh
    - (utente root)     apt install openssh-server
    - (Utente non root) sudo apt-get install openssh-server
2. Installare Apache2
    - (utente root)     apt-get install apache2
    - (utente non root) sudo apt.get install apache2
3. Impostare ip statico
    - (utente root)     nano /etc/netplan/ *nome file*
    - (utente non root) sudo nano /etc/netplan/ *nome file*
  Ci sono svariati nomi di questi file nel mio caso è *01-netcfg.__yaml__*.
  Comunque vengono tutti distinti dall'estensione **yaml**.
  Una volta entrati dentro l'editor modifichiamo questo file in questo modo:
  ```
  
