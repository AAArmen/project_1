FROM python:3.12
WORKDIR /app
COPY . .
RUN pip3 install -r requirements.txt
CMD gunicorn --bind 0.0.0.0:8888 app:app  
