# SUDO

Enable sudo on Debian machine

## Steps:
1) SSH to your server
2) Set root password using `passwd`
3) Create `{{ user }}` using `adduser`
4) Create `hosts` file for your machine
5) Define `{{ user }}` in file in `host_vars` directory
  - If you don't know how to do `5)` & `6)` you can see examples
