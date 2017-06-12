# my_aws
# set below parameeter in /etc/ansible/ansible.cfg

#Add private key of ec2 instance or VM to access
1. private_key_file = /root/couchbase/vm/stage.pem

#To skipp ssh public key to yes
2. host_key_checking = False

3. Add your AWS keys
[root@amit-server my_aws]# ll ~/.aws/
total 8
-rw------- 1 root root  69 Jun  5 07:46 config
-rw------- 1 root root 224 Jun  7 05:25 credentials
[root@amit-server my_aws]#

