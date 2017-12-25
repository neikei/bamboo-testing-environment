# bamboo-testing-environment

Bamboo testing environment in a Vagrantbox based on Debian and provisioned with Ansible.

:warning: Bamboo is a CI software developed by [Atlassian](https://www.atlassian.com/). This is just a free-to-use testing environment to get a first impression and you need an [official Bamboo evaluation license](http://www.atlassian.com/ex/generatelicense.jspa?product=bamboo)!

## Requirements

- Virtualbox >= 5.2.4
- Vagrant >= 2.0.1
- Vagrant Plugin: [vagrant-vbguest](https://github.com/dotless-de/vagrant-vbguest)

## Getting started

1. git clone https://github.com/neikei/bamboo-testing-environment.git
2. cd bamboo-testing-environment
3. vagrant up
4. ... wait ...
5. Open Bamboo in your web browser: http://192.168.56.151
6. Enter your official Bamboo evaluation license
7. Start the "Express installation"
8. Test Bamboo by your own

## Feedback, Issues and Pull-Requests

Feel free to report issues, fork this project and submit pull requests.