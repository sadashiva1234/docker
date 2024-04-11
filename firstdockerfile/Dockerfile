FROM ubuntu:latest
WORKDIR  /app
COPY . /app
RUN apt-get update && apt-get install -y python3 python3-pip
ENV NAME World
CMD ["python3","app.py"] 
FROM debain:latest
WORKDIR /app1
COPY  . /app1
RUN apt update && apt install -y python3 python3-pip
ENV NAME add
CMD ["python3","app1.py"]