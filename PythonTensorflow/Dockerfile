FROM python:3.7

WORKDIR /app
ADD ./requirements.txt /app/requirements.txt
LABEL author="rubenstein.ian@gmail.com"
RUN pip install -r requirements.txt
ENTRYPOINT [ "python3", "-m", "jupyter","notebook", "--ip=0.0.0.0", "--port=8888", "--allow-root"]