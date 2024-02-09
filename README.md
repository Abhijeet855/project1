curl -s https://packages.cloud.google.com/apt/doc/apt-key.gpg | apt-key add -
sudo echo deb http://apt.kubernetes.io/ kubernetes-xenial main > /etc/apt/sources.list.d/kubernetes.list

