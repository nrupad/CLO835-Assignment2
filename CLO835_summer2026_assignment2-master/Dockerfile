FROM python:3.14-slim

WORKDIR /app

COPY apps/python/ .

RUN pip install -r requirements.txt

EXPOSE 8080

CMD ["python", "app.py"]
