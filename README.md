# aws


## 1. STRESS
yum install stress
    4  amazon-linux-extras install epel -y
    5  yum install stress
    6  sudo stress --cpu  8 --timeout 20
    7  sudo stress --cpu  8 --timeout 20
    8  sudo stress --cpu  8 --timeout 20
    9  sudo stress --cpu  8 --timeout 20
   10  sudo stress --cpu  8 --timeout 20
   11  sudo stress --cpu  8
   12  sudo stress --cpu  8
   13  yum update
   14  yum install awscli
   15  awscli version
   16  awscli --version
   17  awscli -v
   18  aws configure
   19  aws configure
   20  aws s3 ls
   21  aws configure
   22  aws s3 ls
   23  clear
   24  aws s3 ls
   25  aws ec2 describe-instances
   26  aws ec2 start-instances --instance-ids i-039288bf706b1cbb5
   27  aws ec2 stop-instances --instance-ids i-039288bf706b1cbb5

---

## 2. STRESS

#STRESS Installation
# Centos
sudo yum install epel-release -y
sudo yum install stress -y

#Amazon Linux 2
sudo amazon-linux-extras install epel -y
sudo yum install stress -y

# Ubuntu
sudo apt update
sudo apt install stress -y

# stress command
stress -c 4 -t 60 && sleep 60 && stress -c 4 -t 60 && sleep 60 && stress -c 4 -t 360 && sleep  && stress -c 4 -t 460 && sleep 30 && stress -c 4 -t 360 && sleep 60
