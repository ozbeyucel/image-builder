FROM centos:7


# installs wget and unzip
RUN yum install wget unzip -y 

#install terraform
RUN wget https://releases.hashicorp.com/terraform/1.4.5/terraform_1.4.5_linux_amd64.zip  && \
    unzip terraform_1.4.5_linux_amd64.zip && \
    chmod +x terraform  && \
    mv terraform  /bin 

