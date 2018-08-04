FROM postgres:9.6

RUN apt-get update \
 && apt-get install -y sqitch postgresql-9.6-repack python3 python3-pip git libpq-dev

RUN python3 -m pip install --upgrade pip
