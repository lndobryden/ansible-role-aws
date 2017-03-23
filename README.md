[![Build Status](https://travis-ci.org/lndobryden/ansible-role-aws.svg?branch=master)](https://travis-ci.org/lndobryden/ansible-role-aws)
Ansible Role AWS
=========

An Ansible role for installing boto3 and setting up aws configuration

Requirements
------------

None

Role Variables
--------------

```
aws_user:
aws_user_home:
aws_default_region:
aws_access_key_id:
aws_secret_access_key:
```

Example Playbook
----------------

```
- { role: aws,
     aws_user: root,
     aws_user_home: root
     default_region: us-east-1,
     aws_access_key_id: key,
     aws_secret_access_key: secret }
```
License
-------

BSD

Author Information
------------------

Lee Dobryden - https://github.com/lndobryden
