docker root sftp
================

https://hub.docker.com/r/salyh/root-sftp/

Docker SFTP server with root access enabled!

-- CAUTION: use for testing only, this is a very insecure setup ---

## Usage
* docker pull salyh/root-sftp
* docker run -p 8767:22 -d salyh/root-sftp
* ssh -p 8767 root@localhost (Password is: root)
* sftp -P 8767 root@localhost (Password is: root)
