FROM python:3.11-alpine
WORKDIR /app
COPY . .
RUN pip install flask redis
CMD ["python", "main.py"]
