+++
title = 'AWS Ansible Deployment'
date = 2024-02-24T09:39:51-05:00
draft = false
weight = 1
summary = 'Use Ansible to run a playbook that will provision AWS infrastructure and install Ansible Automation Platform on that infrastructure in a single command.'
+++

These examples are intended to be modified and updated for individual uses as there is no one-size-fits-all deployment model for Ansible.  The  machine shapes, the database service, and networking configuration will all depend on organizational circumstances.

### Ansible Example

The Ansible example uses Ansible collections, like `amazon.aws` to deploy the AWS infrastructure to run AAP.