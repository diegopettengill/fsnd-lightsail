# Linux Server configuration
Project for Udacity's Full Stack Nanodegree module

### Public IP
54.174.167.17

### PORT
2200

### Hosted application
http://ec2-54-174-167-17.compute-1.amazonaws.com/


## Instaled Softwares
- git
- postgresql
- apache2
- libapache2-mod-wsgi
- pip
- flask
- oauthlib

## Configuration-changes

### Ports

Port was changed from 22 to 2200, with both Lightsail- and UFW-firewalls changes to allow only SSH, HTTP and NTP as per instructions.

### Authorization

New user with account-name called *grader*, with *sudo*-access, only allowed to connect over SSH.

### PostgreSQL

Only allowing local connections. New user called *catalog* which only has limited access to the database *catalog*.


### Third Party Resources used

- [PostGreSQL-documentions](https://www.postgresql.org/docs/)
- [Lightsail-documentation](https://lightsail.aws.amazon.com/ls/docs/all)
- StackOverflow
- Google
- Udacity-community