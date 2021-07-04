# Ansible Playbook for Ubuntu Autoinstall

## What does it do?
This playbook generates an ISO and does all the steps needed for a successful automatic installation of your machine.

You provide the user-data install file and name it autoinstaller. It is up to you if you want to use variables and templating. My example is added.

The base of the steps are by s3rj1k. I've used his gist and conformed it to a playbook with some small changes to make it work in ansible. His gist can be found here with some other examples for user-data files. https://gist.github.com/s3rj1k/55b10cd20f31542046018fcce32f103e