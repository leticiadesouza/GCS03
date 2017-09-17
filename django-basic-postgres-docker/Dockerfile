	
FROM python:2

 # author
 MAINTAINER Letícia de Souza

  ENV PYTHONUNBUFFERED 1 \
      LANG=pt_BR.UTF-8 \
      LANGUAGE=pt_BR:pt \
      LC_ALL=pt_BR.UTF-8

  RUN apt-get update \
     && apt-get -y install \
        python3-pip \
        libpq-dev \
        python-dev


 RUN pip3 install \
	django \
	flake8 \
	psycopg2

RUN mkdir code/
COPY . code/
