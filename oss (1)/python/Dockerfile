FROM ubuntu
RUN apt-get update -y && \
    apt-get install -y python3.6 && \
    apt-get install -y python3-pip python3-dev
    
WORKDIR /app

COPY . /app
CMD ["python3" , "app.py"]
