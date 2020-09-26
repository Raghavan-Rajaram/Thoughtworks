# Thoughtworks.
Running MediaWiki on Ansible 

http://www.mediawiki.org/wiki/Manual:Running_MediaWiki_on_Red_Hat_Linux


Step1 :

Create the ansible role role-name thoughtworks

root@kmaster:~# cd roles/

root@kmaster:~# ansible-galaxy init thoughtworks

root@kmaster:~/roles# tree thoughtworks
thoughtworks
├── defaults
│   └── main.yaml
├── files
├── handlers
│   └── main.yml
├── meta
│   └── main.yml
├── README.md
├── tasks
│   └── main.yml
├── templates
├── tests
│   ├── inventory
│   └── test.yml
└── vars
    └── main.yml

8 directories, 8 files
