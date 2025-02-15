FROM python:3.11.11-slim-bookworm

ENV PYTHONDONTWRITEBYTECODE=1
ENV PYTHONUNBUFFERED=1

WORKDIR /code

# Install Python dependencies
COPY requirements.txt /code/
RUN pip install -r requirements.txt

COPY . /code/