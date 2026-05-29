FROM ubuntu:latest

RUN apt-get update
RUN apt-get upgrade -y
RUN apt-get -y install python3 python3-pip
RUN pip3 install flask --break-system-packages
RUN pip3 install flask_cors --break-system-packages
WORKDIR /app
COPY ./api.py /app/api.py

EXPOSE 5252

CMD ["python3", "api.py"]