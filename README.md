# SUDO

Enable sudo on Debian machine

## Steps:
1) Modify `hosts`
2) Modify `host_vars/`
3) Run `ansible-playbook -i hosts playbook.yml`

## Password
1) Run `sudo pip install passlib`
2) Run `python -c "from passlib.hash import sha512_crypt; import getpass; print sha512_crypt.encrypt(getpass.getpass())"`
