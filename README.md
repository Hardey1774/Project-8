# Project-8
UPDATING Ubuntu Server
<img width="870" alt="1 updating" src="https://user-images.githubusercontent.com/111874994/203747227-cfc900e7-4e7b-49a2-adcd-89229c76b63a.PNG">

INSTALLING APACHE2
<img width="856" alt="2 installing apache2" src="https://user-images.githubusercontent.com/111874994/203747448-0f0c6a5b-12c9-4d63-bc5d-51aa142c6812.PNG">

INSTALLING LIB
<img width="856" alt="3 installing lib" src="https://user-images.githubusercontent.com/111874994/203747593-ecc12fac-58ed-4e58-adc4-62a6d738a9b1.PNG">


INSTALLING MODULES
<img width="861" alt="4 installing modules" src="https://user-images.githubusercontent.com/111874994/203747813-21ab78db-bd46-4983-9bbb-c32d9665183d.PNG">


APACHE2 RUNNING, CHECKING WITH sudo systemctl status apache2
<img width="861" alt="5 apache2 running" src="https://user-images.githubusercontent.com/111874994/203748053-cb15cb22-d8ba-41b9-8d7a-0459b7e607d7.PNG">


CONFIG FILE
<img width="859" alt="6 config file" src="https://user-images.githubusercontent.com/111874994/203748207-be81f276-b525-452a-a4f6-bcc951775b17.PNG">



APACHE2 RUNNING after configuring with: sudo vi /etc/apache2/sites-available/000-default.conf
<img width="857" alt="7 apache2 running after config" src="https://user-images.githubusercontent.com/111874994/203748886-1080df30-8391-4b15-9157-39113d789263.PNG">


UPDATING CONF FILE 
<img width="861" alt="8 configuration" src="https://user-images.githubusercontent.com/111874994/203749040-b39d371a-9b09-4f96-b4cd-c7457d5f944e.PNG">


RUNNING ACCESS-LOG on both web servers: sudo tail -f /var/log/httpd/access_log  
<img width="858" alt="8 running access log web1" src="https://user-images.githubusercontent.com/111874994/203749460-6cb7fb1a-5b7e-4d81-badf-9305247abc81.PNG">
<img width="851" alt="8 running access log web 2" src="https://user-images.githubusercontent.com/111874994/203749877-a56ad6e9-e95c-4ba6-98d7-5132bf74dcb1.PNG">

RUNNING access-log on phones
<img width="960" alt="10 access-log on phones" src="https://user-images.githubusercontent.com/111874994/203750076-86f2b930-2208-4a16-953c-d093f3f963d1.PNG">



CHECKING BROSWER WITH LOADBALANCER IP ADDRESS
<img width="953" alt="9 checking browser through the loadbalancer pub IP" src="https://user-images.githubusercontent.com/111874994/203750293-8f716c2a-3e14-4694-b69c-264018cda5f0.PNG">


UPDATING HOST FILE: sudo vi /etc/hosts
<img width="957" alt="11 updating host file" src="https://user-images.githubusercontent.com/111874994/203750421-ca4f8be2-ff31-40cd-8d45-77c1a3673667.PNG">


UPDATING APACHE CONF FILE: sudo vi /etc/apache2/sites-available/000-default.conf
<img width="960" alt="12 updating apache conf file with web1 and web2" src="https://user-images.githubusercontent.com/111874994/203750704-9c825256-c369-4024-b7bf-a94f63a63bd7.PNG">



CURL ON LB FOR WEB1: curl http://Web1
<img width="957" alt="13 curl on LB for web1" src="https://user-images.githubusercontent.com/111874994/203751019-5c5cd9ad-aeb8-45c6-9d61-6a644a881bfd.PNG">


CURL ON LB FOR WEB2: curl http://Web2
<img width="960" alt="14 curl on LB for web2" src="https://user-images.githubusercontent.com/111874994/203751548-e8123f53-bab3-4c87-a04b-c1eb407bc49c.PNG">



