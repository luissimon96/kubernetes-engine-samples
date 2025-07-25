FROM python:3.14.0rc1-slim
COPY . .
RUN pip install -r requirements.txt
ENTRYPOINT ["python", "-u", "main.py"]
