# Patra AWS Terraform Project


# Requirements Cloud Provider
Free tier offerings are available from Amazon, Microsoft, Google, etc. If, however, you are unable to take advantage of a free tier offering, a temporary cloud environment can be provided to you.
Hosted Code Repository
Free tier offerings are available from GitHub, Bitbucket, GitLab, etc.
Continuous Integration Platform
Free tier and open source tools exist like GitHub Actions, Jenkins, Circle CI, etc.
Orchestration & Configuration Management Tooling
Free tier and open source tools exist like Terraform, CloudFormation, Packer, Ansible, Chef, etc.


# Assignment
• Create a simple, yet resilient application, which responds to HTTP requests.
• The application should allow for individual node failures, without impacting availability.
• The application should be able to scale based on load.
• Underlying cloud infrastructure should be defined as code, stored in a repository, with
instructions about how it should be built.
• Changes to code should result in the triggering of a simple continuous integration test.
• A successful CI test should trigger an automated deployment.
• Implement a simple degree of monitoring & logging.


# Used Resources in .tf files 
Provider = Amazon Web Services (AWS)
Network  = VPC, Internet Gateway, Subnet, Route Table, aws_route_table_association, Elastic IP and Security Groups
S3 buckets
Application Load Balancer = Target Group, Target Group Attachment, Load Balancer, LB_listeners
Default Page = ami Data Block, ec2
Autoscaling = Launch_configuration, Autoscaling_policy, Autoscaling_group, Cloudwatch_metric_alarm, Autoscaling_attachment

