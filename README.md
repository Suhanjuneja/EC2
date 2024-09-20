# AWS 

**What is AWS ?**

AWS, or Amazon Web Services, is a comprehensive cloud computing platform provided by Amazon. It offers a wide range of services including computing power, storage options, database management, machine learning, and more. Businesses use AWS to host applications, store data, and scale their operations efficiently.

**How to make Virtual Machine**

1.Make an aws account

2.select EC2 service and make an instance.

3.For instance select Opertaing system(preferable LINUX-UBUNTU)

![image alt](https://github.com/Suhanjuneja/EC2/blob/5326213ba7c86f7e16fb72120c1801ccf498308a/Screenshot%20(123).png)

4.Make a Key pair( while making it select ppk type)

![image alt](https://github.com/Suhanjuneja/EC2/blob/2797d6d08bd3f397799b4a9c1da8caebfc0d99ae/Screenshot%20(125).png)

5.launch the instance

6.A public ip adress will be generated,copy this.

![image alt](


7.Install putty after that opt for ssh option paste the ip copied earlier ,then auth ,then credentials, then browse for the key you saved.

8.A window will open type UBUNTU

9.Now to download a web server type ls , [ sudo apt update ] , after that type [sudo apt install apache-2]

10.To remove dollar sign type [sudo su] 

11.After that next step is to type-[/var/www/html/]

12. After pressing enter type [index.html]

13. then type-[rm index.html], then press enter
    
14.THEN type -[vi index.html]

15.This upper process will lead in opening of new page.

16. type html code

17.  <html>
  hii
  </html>

18.To run the code type - [control+c,shift+q, and press enter]
