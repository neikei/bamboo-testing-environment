# bamboo-testing-environment

Bamboo testing environment in a Vagrantbox based on Debian and provisioned with Ansible.

:warning: Bamboo is a CI software developed by [Atlassian](https://www.atlassian.com/). This is just a free-to-use testing environment to get a first impression and you need an [official Bamboo evaluation license](http://www.atlassian.com/ex/generatelicense.jspa?product=bamboo)!

## Requirements

- Virtualbox >= 5.2.4
- Vagrant >= 2.0.1
- Vagrant Plugins:
  - vagrant plugin install vagrant-hostmanager
  - vagrant plugin install vagrant-vbguest

## Getting started

1. git clone https://github.com/neikei/bamboo-testing-environment.git
2. cd bamboo-testing-environment
3. vagrant up
4. ... wait ...
5. Open Bamboo in your web browser: http://bamboo.test
6. Enter your official Bamboo evaluation license
7. Start the "Express installation"
8. Test Bamboo

## Feedback, Issues and Pull-Requests

Feel free to report issues, fork this project and submit pull requests.