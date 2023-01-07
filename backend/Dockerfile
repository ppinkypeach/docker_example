FROM python:3.10-slim

WORKDIR /feedme
COPY requirements.txt /feedme

RUN pip install --upgrade pip
RUN pip install -r requirements.txt 

COPY . /feedme/

ENTRYPOINT [ "python", "main.py" ]