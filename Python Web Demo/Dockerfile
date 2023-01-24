FROM python:3

WORKDIR /usr/src/app

COPY requirements.txt ./
RUN pip install --no-cache-dir -r requirements.txt

COPY app .

EXPOSE 8080/tcp

CMD [ "python", "./simple-web-app.py" ]