FROM php:8.2-cli

RUN apt-get update && apt-get install -y nodejs npm

COPY . /usr/src/app
WORKDIR /usr/src/app
RUN npm install onchange -g
CMD ["make", "test.watch"]
