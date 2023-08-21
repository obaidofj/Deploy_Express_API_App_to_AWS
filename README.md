# Steps for deploying Express API to AWS

## First Creating Lunch template
 
![image 1](images/1.jpg)
 
### Lunch template is to make an instance we select or create new keypairs and security group
![image 2](images/2.jpg)

## Then we Create auto scale group
### And we Choosed launch template 
### also instance launch options And availability zoon
![image 3](images/3.jpg)

## We create new load balancer then we go back and associate  auto scale group with it
![image 4](images/4.jpg)
 

## Then the app deployed and worked from an instance ip :
![image 5](images/5.jpg)

 ![image 6](images/6.jpg)
### This is the health of target group:
 
![image 7](images/7.jpg)



## Then the app worked from load balancer dns name :
 
![image 8](images/8.jpg)

 ![image 10](images/10.jpg)
