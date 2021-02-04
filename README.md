Please follow the live [document](https://docs.google.com/document/d/17OwlITE-yPWNj3Vi5RtQfz3ItvSkOfnbaVMnzlZyGTg)

To go about doing this project first we need to create an empty Dockerhub Repository


Next we need to setup a Jenkins pipeline that can run commands on your local machine

To install Jenkins you need to install pip first by running theese commands

sudo apt update

sudo apt install python3-pip

pip3 --version 
To check if pip successfully installed

Install Jenkins

wget -q -O - http://pkg.jenkins-ci.org/debian/jenkins-ci.org.key | sudo apt-key add -

sudo sh -c 'echo deb http://pkg.jenkins-ci.org/debian-stable binary/ > /etc/apt/sources.list.d/jenkins.list'

sudo apt update

sudo apt install jenkins

TO START JENKINS

sudo systemctl start jenkins

sudo systemctl status jenkins


sudo ufw allow 8080

sudo ufw status

Now open up your internet browser and go to http://localhost:8080

To get password
sudo cat /var/lib/jenkins/secrets/initialAdminPassword


