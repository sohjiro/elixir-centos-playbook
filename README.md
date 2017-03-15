# Elixir + Phoenix framework on CentOS 7 playbook

### WIP Alert 
This is a work in progess, but please feel free to test and help :)

## Introduction

CentOS 7 is a state-of-the-art, enterprise-ready distribution and our choice for running our Phoenix application.
We use Ansible to configure our server(s) and deploy our app.

This playbook will be made of two parts: 

* Getting machines ready to run Elixir and Phoenix framework
* Deploying (continuously, eventually) our app, run db migrations, assets compilations, etc.

## Setup

Assuming you know your way around installing ansible and running ansible-playbook.
You need to create two files before running: `ansible.cfg` and `inventory`

(See `ansible.cfg.example` and `inventory.example` for examples)

## Running the setup part
`ansible-playbook setup.yml` :)

## Contributing
Please do !

Next on the plate: Deploying a phoenix framework app.
