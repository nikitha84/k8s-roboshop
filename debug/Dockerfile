FROM almalinux:9
RUN dnf install net-tools telnet iputils bind-utils -y
RUN useradd roboshop
USER roboshop
CMD ["sleep", "1000"]

#build image
#docker build -t nikitha84/debug:v1 .
#docker push nikitha84/debug:v1
#create a debug pod
