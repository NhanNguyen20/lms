# Use the official Frappe Bench image as a parent image
FROM frappe/bench:latest

# Copy the init.sh script into the container
COPY ./init.sh /init.sh

# Make the init.sh script executable
RUN sudo chmod +x /init.sh

# Set the working directory in the container
WORKDIR /home/frappe

# Run the init.sh script
CMD ["/bin/bash", "/init.sh"]