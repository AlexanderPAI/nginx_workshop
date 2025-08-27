FROM python:3.13-slim

WORKDIR /app

COPY ./api_2 .

RUN ls

RUN pip install -r requirements.txt

CMD ["uvicorn", "main:app", "--port", "8001", "--host", "0.0.0.0"]
