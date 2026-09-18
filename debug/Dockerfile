FROM almalinux:9
RUN dnf install telnet net-tools iputils bind-utils -y
RUN useradd prints
USER prints
CMD ["sleep", "100000"]