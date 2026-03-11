FROM almalinux:9
RUN dnf install telnet net-tools iputils bind-utils -y
RUN useradd roboshop 
# we need to run as non root user bcz dhiki access vachhina migathavatiki vachhinate 
USER roboshop
CMD ["sleep", "1000000"]