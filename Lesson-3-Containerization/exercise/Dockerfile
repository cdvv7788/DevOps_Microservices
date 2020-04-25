FROM python:3.8.2-buster

WORKDIR /app

COPY . app.py /app/

RUN pip install --upgrade pip &&\
    pip install --trusted-host pypi.python.org -r requirements.txt

EXPOSE 5000

CMD ["python", "app.py"]
