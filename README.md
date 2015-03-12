ansible-docker
==============

[![Build Status](https://travis-ci.org/infoslack/ansible-docker.svg?branch=master)](https://travis-ci.org/infoslack/ansible-docker)

Recipe for Ansible install Docker

### Setup

	$ git clone git@github.com:infoslack/ansible-docker.git
	$ cd ansible-docker
	$ cp hosts.example hosts

- Edit `hosts` and include the name servers;
- You can chage the rules or the order of execution in `server.yml`

### Run

	$ ansible-playbook -i hosts server.yml
