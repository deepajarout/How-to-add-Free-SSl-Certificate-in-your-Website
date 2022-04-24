# How to add free ssl certificate in your website

## Introduction
Any website that aspires to attract visitors needs to include SSL/TLS encryption for its domain. SSL/TLS certificates ensure a safe connection between your web server and browsers.

Let’s Encrypt is a free certificate authority that allows you to set up such protection. It is the simplest way to secure your Nginx server.

## Step 1: Install Certbot

Certbot is an open-source software tool for automatically enabling HTTPS using Let’s Encrypt certificates.

The first step to securing Nginx with Let’s Encrypt is to install Certbot. To do so, start by opening a terminal window and updating the local repository:

` sudo apt update `
