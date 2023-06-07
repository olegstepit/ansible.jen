FROM ubuntu:22.04
#ENV DEBIAN_FRONTEND=noninteractive
#ENV TZ=Europe

RUN apt-get update && apt-get install -y software-properties-common
RUN apt-add-repository -y ppa:ansible/ansible
RUN apt-get update && apt-get install -y ansible

 

#RUN rm /etc/ansible/ansible.cfg
#COPY ansible.cfg /etc/ansible/ansible.cfg
#RUN rm /etc/ansible/hosts
#RUN rmdir /etc/ansible/roles
#RUN mkdir /etc/ansible/hosts
#COPY step /etc/ansible/hosts/step

 


CMD ["/bin/bash"]
