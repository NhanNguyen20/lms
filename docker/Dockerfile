FROM nhan2102/bench:latest

COPY ./init.sh /init.sh

RUN sudo chmod +x /init.sh

# Set the working directory in the container
WORKDIR /home/frappe

EXPOSE 8000 9000

CMD ["/bin/bash", "/init.sh"]