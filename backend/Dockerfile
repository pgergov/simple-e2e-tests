FROM python:3.6.2

RUN mkdir app
WORKDIR /app
RUN git clone https://github.com/pgergov/simple-django-rest-api.git
WORKDIR ./simple-django-rest-api
RUN pip install -r requirements.txt

RUN curl -O https://raw.githubusercontent.com/vishnubob/wait-for-it/master/wait-for-it.sh
RUN chmod +x ./wait-for-it.sh
