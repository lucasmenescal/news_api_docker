FROM python:3.10-bullseye

ENV PYTHONDONTWRITEBYTECODE=1
ENV PYTHONUNBUFFERED=1

WORKDIR /workspace/requirements/
COPY requirements.txt /workspace/requirements/

RUN pip install --upgrade pip
RUN pip install -r requirements.txt

WORKDIR /workspace
