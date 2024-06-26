# Sysadmin - Interview

Before you start, please get the server IP from the interviewer and give them your SSH public key. If you don't know how to complete a specific task or you are stuck, please ask the interviewer for help.

This repo contains a number of tasks that you will need to complete, all of them are given below:

## Configuring a Firewall

Configure the firewall to block port 80/443 for all incoming traffic except for the following IP addresses:

```
210.89.55.24/32
2402:e280:2125:2ac::/64
```

## Troubleshooting Nginx

An nginx server is installed on the server, due to a misconfiguration, the server is not running. Please fix the issue and start the nginx server.


## Setting up a Rustdesk Relay with Docker

You need to setup a Rustdesk Relay server on the server. You can use [this](https://rustdesk.com/docs/en/self-host/rustdesk-server-oss/docker/) guide to setup the server. Please make sure that the server is using it's default ports bindings.

## Setup a wireguard server

You need to setup a wireguard server and create a peer configuration for the interviewer. The port used should be 51820.

----

You can document your thought process and also how you solved the problems in a separate markdown file and submit it to the interviewer.

There is a time limit of 3 hours for this task. Please make sure to complete the tasks within the time limit.