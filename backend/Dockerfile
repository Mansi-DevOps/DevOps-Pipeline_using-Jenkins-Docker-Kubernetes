FROM python:3.9
WORKDIR /app
RUN apt-get update && apt-get install -y
COPY . /app

RUN pip install -r requirements.txt
EXPOSE 5000
CMD [ "python", "app.py"]

