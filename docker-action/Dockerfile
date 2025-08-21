
FROM alpine:latest

LABEL "maintainer"="yourname@example.com"
LABEL "description"="A simple Docker-based GitHub Action"

RUN apk add --no-cache bash curl
#copying 
COPY entrypoint.sh /entrypoint.sh
RUN chmod +x /entrypoint.sh

ENTRYPOINT ["/entrypoint.sh"]

