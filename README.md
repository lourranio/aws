# aws


## 1. STRESS

```
yum install stress
```

```
 amazon-linux-extras install epel -y
 yum install stress
 sudo stress --cpu  8 --timeout 20
 sudo stress --cpu  8 --timeout 20
 sudo stress --cpu  8 --timeout 20
 sudo stress --cpu  8 --timeout 20
 sudo stress --cpu  8 --timeout 20
 sudo stress --cpu  8
 sudo stress --cpu  8
 yum update
 yum install awscli
 awscli version
 awscli --version
 awscli -v
 aws configure
 aws configure
 aws s3 ls
 aws configure
 aws s3 ls
 clear
 aws s3 ls
 aws ec2 describe-instances
 aws ec2 start-instances --instance-ids i-039288bf706b1cbb5
 aws ec2 stop-instances --instance-ids i-039288bf706b1cbb5
```

---

## 2. STRESS

STRESS Installation

### Centos

```
sudo yum install epel-release -y
sudo yum install stress -y
```

### Amazon Linux 2
```
sudo amazon-linux-extras install epel -y
sudo yum install stress -y
```

### Ubuntu
```
sudo apt update
sudo apt install stress -y
```

### stress command
```
stress -c 4 -t 60 && sleep 60 && stress -c 4 -t 60 && sleep 60 && stress -c 4 -t 360 && sleep  && stress -c 4 -t 460 && sleep 30 && stress -c 4 -t 360 && sleep 60
```

## 3 . Amazon S3 Transfer Acceleration Speed Comparison

This speed checker uses multipart uploads to transfer a file from your browser to various Amazon S3 regions with and without Amazon S3 Transfer Acceleration. It compares the speed results and shows the percentage difference for every region.

Note: In general, the farther away you are from an Amazon S3 region, the higher the speed improvement you can expect from using Amazon S3 Transfer Acceleration. If you see similar speed results with and without the acceleration, your upload bandwidth or a system constraint might be limiting your speed.

http://s3-accelerate-speedtest.s3-accelerate.amazonaws.com/en/accelerate-speed-comparsion.html

## 4 . Metadata 

169.254.168.254/latest/meta-data
