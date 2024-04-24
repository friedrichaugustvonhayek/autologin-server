# installation

buy the required files at [bitcoin-kleinanzeigen.cc](https://bitcoin-kleinanzeigen.cc/wordpress/?product=own-your-own-lernplattform-autologin-server)  


install webserver (i am running apache2)  
install database  (i am running mariadb)  
install php plugin for webserver and activate php module in webserver config  

[linux instructions](https://www.digitalocean.com/community/tutorials/how-to-install-lamp-stack-on-ubuntu)  

rent a vps if you havent already.  
choose and install an web hosting control panel and register a domain.  
- upload the files to your server working directory.  
- run seedPython.sh  
- execute seed.sql in db-program:  
    - enter db-program with `sudo mariadb` if you have choosen mariadb-server as database program.  

i tested exact these procedure and can verify that it works.  
now everything is up and running. edit the contacts.html page to your needs.  
