# Ansible Realtime project
Ansible project using three tasks. 
Use Ansible to create Three EC2 instances, one of type Amazon Linux and 2 instances of types Ubuntu. Make sure to secure the AWS credentials in Ansible vault.
Setup passwordless authentication with the created EC2 instances. 
Shutdown only selected EC2 instances using Ansible conditionals (When condition).

[all]
ec2-user@13.232.240.213
ubuntu@65.2.167.175
ubuntu@13.232.48.111

## Task 1

Create three(3) EC2 instances on AWS using Ansible loops
- 2 Instances with Ubuntu Distribution
- 1 Instance with Centos Distribution

Hint: Use `connection: local` on Ansible Control node.

## Task 2

Set up passwordless authentication between Ansible control node and newly created 
instances.

## Task 3

Automate the shutdown of Ubuntu Instances only using Ansible Conditionals

Hint: Use `when` condition on ansible `gather_facts`
