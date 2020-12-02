FROM python:3
FROM tensorflow/tensorflow:1.8.0-py3
WORKDIR /usr/src/app
COPY requirements.txt ./
RUN pip install --no-cache-dir -r requirements.txt
COPY . .
CMD [ "python", "app.py" ]
