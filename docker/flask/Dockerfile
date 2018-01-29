FROM debian:latest
RUN apt-get update -y && \
    apt-get install -y python-pip python-dev build-essential vim net-tools

RUN pip install flask
#COPY app /flask_app
WORKDIR /flask_app
# TODO - entrypoint.sh
CMD ["python", "flask_app.py"]
