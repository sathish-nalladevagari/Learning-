Today is the day 4 and learning some vms using vagrant 

and how to setup vagrant images 
and vagrant commands such as 
1. vagrant up
2. vagrant halt
3. vagrant ssh
4. vagrant status
5. vagrant provision
6. vagrant destroy
7. vagrant global-status


And installed httpd to run server on local
and apache2 or LAMP stack like apache2,mysql,php,wordpress templete for ubuntu 

I have created a httpd server and set up a web page locally
and These are step by step process

1. create a vm of centos named website name
2. setup local address of vagrant file using vim or any editor
3. now install required dependencies 
     yum install vim wget unzip zip httpd -y
4. now run a server of httpd using command 
    systemctl start httpd by enabling them using systemctl enable httpd
5. now set up your index.html page in /var/www/html
6. reboot the server
7. check the server in your local browser
![Screenshot 2023-09-18 000317](https://github.com/sathish-nalladevagari/Learning-Devops/assets/104757035/3d6bc523-5167-4d75-97b1-ab1b311be322)
