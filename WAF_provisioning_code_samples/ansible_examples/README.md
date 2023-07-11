# Ansible Playbook samples

### Introduction
 
[Ansible](https://www.ansible.com/) is a configuration management software. 

### How it's different
 
From Ansible's website: It uses no agents and no additional custom security infrastructure, so it's easy to deploy - and most importantly, it uses a very simple language (YAML, in the form of Ansible Playbooks) that allow you to describe your automation jobs in a way that approaches plain English.

### What's this space all about?

This space contains Ansible playbook samples that can be used for provisioning and configuring Barracuda WAF instances on AWS and Azure.

### Content:  
1. waf_config_sample.yml: Sample ansible playbook that can be used to create a service on a Barracuda Web Application Firewall using the built in URI module.
The module calls the Barracuda REST APIv1 for logging in with a restapi token, and then creates a service.
[RESTAPI documentation can be found here](https://campus.barracuda.com/product/webapplicationfirewall/article/WAF/RESTAPI/)

2. waf_ec2.yml: Creates a Barracuda WAF EC2 instance on AWS

3. azure_vm_create.yaml: Creates a Barracuda WAF VM, a storage account, NIC interface and a NSG on Microsoft Azure in a resource group.

### Additional References

1. [URI module](http://docs.ansible.com/ansible/latest/uri_module.html)
2. [AWS ec2 module](http://docs.ansible.com/ansible/latest/ec2_module.html)
3. [Microsoft azure_rm deployment module](http://docs.ansible.com/ansible/latest/azure_rm_deployment_module.html)



##### DISCLAIMER: ALL OF THE SOURCE CODE ON THIS REPOSITORY IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL BARRACUDA BE LIABLE FOR ANY CLAIM, DAMAGES, OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOURCE CODE.
 

