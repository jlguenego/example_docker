FROM rastasheep/ubuntu-sshd:14.04

COPY authorized_keys /root/.ssh/authorized_keys

RUN passwd -d root
RUN chown root:root /root/.ssh/authorized_keys
