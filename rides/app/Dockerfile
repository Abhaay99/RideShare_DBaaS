FROM python:3.6
EXPOSE 8000

WORKDIR /app

COPY requirements.txt /app
RUN pip install -r requirements.txt

COPY assignment1.py /app
COPY AreaNameEnum.csv /app
COPY count_reqs.txt /app