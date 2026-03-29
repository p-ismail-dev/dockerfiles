FROM almalinux:9
RUN dnf install nginx -y
# required root access to create user or install pacakges
RUN useradd roboshop

USER roboshop
CMD ["sleep" , "100"]