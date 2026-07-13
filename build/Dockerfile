FROM python:3.10-alpine

WORKDIR /app

COPY app/requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt

COPY app/*.py .

EXPOSE 8000

CMD ["python3", "app.py"]
