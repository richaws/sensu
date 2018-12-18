FROM rabbitmq

# Define environment variables.
ENV RABBITMQ_USER sensu
ENV RABBITMQ_PASSWORD 1992

ADD init.sh /init.sh
EXPOSE 15672/tcp 25672/tcp 4369/tcp 5671/tcp 5672/tcp

# Define default command
CMD ["/init.sh"]