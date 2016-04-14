# docker-nginx-redmine-owncloud
You want to deploy some web services for your company. 
Including :      
 *Redmine : a ticketting system     
  *Owncloud for sharing files     
  *The web site of your company : Mashibuya  Your goal is to design a docker file to aggregate all these docker files behind a docker-compose

Add these DNS entry pointing to 127.0.0.1 in your /etc/hosts file : redmine.mashibuya.com, owncloud.mashibuya.com 

RUN: ``` dockercompose up````
