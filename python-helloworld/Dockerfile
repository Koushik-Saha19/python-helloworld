FROM python:3.8
LABEL maintainer="Koushik Saha"

COPY . /app
WORKDIR /app
RUN pip install Flask

RUN pip install werkzeug

# command to run on container start
CMD [ "python", "app.py" ]
