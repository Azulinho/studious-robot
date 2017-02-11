
The `create-s3-bucket.yml` playbook will create an IAM user and a S3 bucket.


To execute that ansible playbook, make sure you use the correct ansible 
version, by following the next steps:


```
git clone https://github.com/ministryofjustice/opg-ansible-roles
virtualenv venv
source venv/bin/activate
pip install -r requirements.txt
ansible-playbook -i inventory/aws/inventory.ini create-s3-bucket.yml
```
