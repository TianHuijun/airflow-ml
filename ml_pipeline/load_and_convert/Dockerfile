FROM python:3.9

COPY requirements.txt data_load.py utils.py /workdir/
WORKDIR /workdir

RUN pip install --no-cache-dir -r requirements.txt