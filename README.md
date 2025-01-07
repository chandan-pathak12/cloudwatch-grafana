Aim : To visualize AWS resources after AWS CloudWatch and Grafana Intergation

Steps to be followed:

1. Installation of grafana on your server. We can refere the link https://grafana.com/docs/grafana/latest/setup-grafana/installation/debian/


2. Create a IAM user for getting secret access key . It will be in use when we will add cloudwatch as datasource in grafana.

IAM policy : 
Create a policy and attach the role with your instnce and resource

![Alt Text](/IAMpolicy.png)

3. 
The whole infra will be look like below

![Alt Text](/Cloudwatch-grafana.png)