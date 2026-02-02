FROM python:3.9-slim-buster

WORKDIR /app

ADD . .

RUN pip install --no-cache-dir -r requirements.txt

CMD ["python", "app.py"]
