FROM ubuntu:20.04
RUN apt update && apt install openssh-server -y
RUN mkdir -p /root/.ssh && \
    mkdir /var/run/sshd && \
    touch /root/.ssh/config && \
    echo "Host *" >> /root/.ssh/config && \
    echo "    StrictHostKeyChecking no" >> /root/.ssh/config
COPY ./server/ssh-keys/id_rsa /root/.ssh/id_rsa