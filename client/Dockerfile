FROM ubuntu:20.04
RUN apt update && apt install openssh-server -y
RUN mkdir -p /root/.ssh
RUN mkdir /var/run/sshd
COPY ./client/ssh-keys/id_rsa.pub /root/.ssh/authorized_keys