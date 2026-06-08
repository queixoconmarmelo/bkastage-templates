FROM python:3.10-alpine

COPY code/app/python-app-main/python-app-main/requirements.txt /tmp

RUN pip install -r /tmp/requirements.txt

COPY code/app/python-app-main/python-app-main/src /src

CMD python /src/app.py

