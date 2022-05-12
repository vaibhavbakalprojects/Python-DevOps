FROM python:3.10.3

WORKDIR /app

COPY requirements.txt requirements.txt

RUN py --version

RUN pip install Django==4.0.4

RUN pip install -r requirements.txt

COPY . .

EXPOSE 8000

CMD [ "python","manage.py","runserver","0.0.0.0:8000" ]