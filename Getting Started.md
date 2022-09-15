
Go to Burp Suite and download the appropriate file for your operating system. I'm currently using Ubuntu 20.01. I'm also downloading the professional version so there is a step for downloading the license. 

![Screenshot from 2022-09-15 22-20-52](https://user-images.githubusercontent.com/113462727/190415170-2e0c9723-c706-4a32-8844-e7454998a1cc.png)


The download should be a file called burpsuite_pro_<os>_<version>.sh 

 ![image](https://user-images.githubusercontent.com/113462727/190415447-03cb5d7f-b66c-4271-81a5-7b0d9f2d9679.png)
 

Open the terminal and cd into the directory where the file is and use the following command: 

 chmod +x burpsuite_community_linux_v<your version here>.sh 
./burpsuite_community_linux_v<your version here>.sh 

 

Use ls command to see that the file can now be executed. Use the following command: 

 


 

./burpsuite_pro_linux_v<your version here>.sh  

 

This starts the installation process 

Setup - Burp Suite professional 2022.8.1 
Select Destination Directory 
Where should Burp Suite Professional be installed? 
Select the folder where you would like Burp Suite Professional to be 
installed, then click Next. 
m6me/blvkhakr/BurpSuiteP/O 
Required disk space: 594 MB 
Free disk space: 
157 GB 
< Back 
Next > 
Browse 
Cancel 
 

Leave everything default unless you want to save the files in a specific location. Then select "Finish" 

 

Setup - Burp Suite professional 2022.8.1 
Completing the Burp Suite 
Professional Setup Wizard 
Setup has finished installing Burp Suite 
Professional on your computer. The application 
may be launched by executing the installed start 
scripts. 
Click Finish to exit Setup. 
Finish 
 

 

There should now be a executable in the folder called BurpSuitePro. To start Burp Suite Pro from terminal use command: 


 

 

./BurpSuitePro 

 

Once it starts, it will ask you for the license  

Burp Suite professional 
Enter license key 
This version of Burp requires a license key. To continue, please paste your license 
key below, or load it from file. 
Select license key file 
 

If you haven't already done so, grab the license from your account 

Product 
Burp Suite Professional 
License key 
Download license 
Latest software 
Download software 
License detail 
 

Upload license to Burp Suite Pro and click Next 

 

If Burp has to access the Internet via a proxy, enter the information here. Otherwise click "Next" 

 

Burp Suite professional 
Activate License 
Burp will now attempt to contact the license server and activate your license. This will 
require Internet access. If you access the Internet Via a web proxy server, please 
enter the details below. 
NOTE: license activations are monitored. If you perform too many activations, further 
activations for this license may be prevented. 
Use proxy server to connect 
Host: 
port: 
Cancel 
Re-enter license key 
Manual activation 
Next 
 

Burp Suite professional 
Success 
Your license successfully installed and activated. 
Finish 
 

Click "Finish". Now you have Burp Suite Pro installed and ready 

O Welcome to Burp Suite Professional. Use the options below to create or open a project. 
O Temporary project 
o 
New project on disk 
o 
Open existing project 
Name: 
File: 
Name 
File: 
Pause Automated Tasks 
Burp Suite 
Professional 
Choose file___ 
File 
Choose file. 
 
