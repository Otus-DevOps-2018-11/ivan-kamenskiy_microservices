FROM python:3.6.0-alpine

WORKDIR /app
ADD . /app

# https://github.com/giampaolo/psutil/issues/1143
# install python-dev
RUN apk add --update \
    python \
    python-dev \
    py-pip \
    musl-dev \
    build-base 
RUN pip install -r /app/requirements.txt

ENV POST_DATABASE_HOST post_db
ENV POST_DATABASE posts

ENTRYPOINT ["python3", "post_app.py"]