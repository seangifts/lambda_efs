```
sudo mkdir -p /mnt/efs/fs1/ml
sudo chown ec2-user:ec2-user /mnt/efs/fs1/ml
sudo yum install -y python3
pip3 install -t /mnt/efs/fs1/ml/lib torch torchvision numpy
sudo chown -R 1001:1001 /mnt/efs/fs1/ml
```
