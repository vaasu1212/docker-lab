FROM python:2.7.11-slim
RUN pip install --upgrade pip
RUN pip install requests flask
COPY . myapp/
WORKDIR myapp
EXPOSE 3000
ENTRYPOINT ["python", "myapp.py"]
