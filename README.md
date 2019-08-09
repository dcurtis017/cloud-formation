https://garbe.io/blog/2017/07/17/cloudformation-hacks/

https://medium.com/boltops/a-simple-introduction-to-aws-cloudformation-part-1-1694a41ae59d

https://github.com/aws-samples/ecs-refarch-cloudformation/blob/master/infrastructure/load-balancers.yaml

https://www.bogotobogo.com/DevOps/AWS/aws-CloudFormation-Autoscaling-Group-ASG-Application-Load-Balancer-ALB-with-Update-Policy-Rolling-Updates.php
# existing
1. basic-vpc
2. basic-vpc-webserver
3. basic-vpc-bastion
4. basic-vpc-nat-gateway


# To add:
1. add user data to webserver instance (done)
2. do another one that uses custom amis and launch template
3. auto scaling group
3. launch template
4. application load balancer
5. add target listener rules for specific cases
6. ecs
7. ability to ssh into web server

___
# Notes
Fn::GetAtt: