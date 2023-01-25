FROM ubuntu:latest

RUN apt-get -y update && \
    DEBIAN_FRONTEND=noninteractive apt-get -y install nodejs && \
    DEBIAN_FRONTEND=noninteractive apt-get -y install yarn

WORKDIR /app
COPY . .

CMD ["node", "src/index.js"]
EXPOSE 8000
