i read the instruction from darey.io
I downloaded a my project file on a website, i download my e-commerce "MarketPeak".
I download it a folder on my local Pc then open my gitbash from the folder
On my gitbash, i registered and created my name and email on the git repository for audit
I git init the repo in my folder, which created my git folder
i add my folders to my git repository, then later track the files by commiting it
Then opened the Github repository, created a new file called MarketPeak, i didnt created the new file with the Readme.md
After which the repository was created. 
I copied this "git remote add origin https://github.com/liwencee/MarketPeak.git" on the Github repository and run on my Gitbash 
Then copied this |git branch -M main" and run on my gitbash
did same for this "git push -u origin main"
then from the folder downloaded i open my visual code, the css folder is open and my logo is inserted using visual code, the size is adjusted accord accordingingly
with this code line 
img {
	width: 110px;
	height: 90px;
	margin-top: -20px;
}
	.footer-logo {
	width: 100px;
	height: 100px;
		}

I used powershell to ssh. gitbash to ec2 usimh=g this command line "cat /home/ubuntu/.ssh/id_rsa.pub"
The key generated was copy and pasted into the SSH key in the Github. then the repositorey was clone on the ec2 instance by running git clone <the github url>
once that is done, we install the webs server using these commands "sudo yum update -y
sudo yum install httpd -y
sudo systemctl start httpd
sudo systemctl enable httpd
"
the wesbite is expected to be stored in the /var/www/html but html was missing so i did make a directory for html after runnung ls to see the list in my directory. I realised no folder in my /var/www/html so i run sudo yum install git to install the git on my ec2 instance, i clone the repo git clone <the github url> after this i ran into another error trying to run sudo rm -rf /var/www/html/*
sudo cp -r ~/MarketPeak_Ecommerce/* /var/www/html/
so i used ls/var/www and then realise html direction was missing, so i run  mkdir / var/ www/html then my ec2 stop throwing errors.
so i paste my ip generated from my instance to check if the website is deploy on my web brouser, i hav error showing the website is faulty somehere.  so i created security group the selected HTTP then port 80 was selected, the website was deployed


  

  




