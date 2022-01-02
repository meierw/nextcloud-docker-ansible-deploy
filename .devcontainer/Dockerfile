FROM registry.gitlab.com/solveri/devcontainer/node-gradle:d11-n16-g7-j17

# Install Ansible.
RUN echo 'deb http://ppa.launchpad.net/ansible/ansible/ubuntu focal main' \
  | tee /etc/apt/sources.list.d/ansible.list
RUN apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 93C4A3FD7BB9C367
RUN apt update \
  && apt install -y ansible
