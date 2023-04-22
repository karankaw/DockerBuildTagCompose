FROM debian:stretch-slim
RUN apt-get update \
    && apt-get install -y python3 
# RUN git clone https://github.com/DChandlerP/python-hello.git
WORKDIR /
COPY ./ .

# CMD ["python3", "/python-hello/hello.py"]
#ENTRYPOINT [ "python3" ]
#CMD ["/python-hello/hello.py"]