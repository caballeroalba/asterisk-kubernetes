FROM python:3.7-alpine
EXPOSE 8000
WORKDIR /app
COPY requeriments.txt /app
RUN pip3 install -r requeriments.txt --no-cache-dir
COPY . /app
ENTRYPOINT ["python3"]
CMD ["manage.py", "runserver", "0.0.0.0:8000"]
