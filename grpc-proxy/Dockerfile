FROM nginx:1.21-alpine

COPY run-proxy.sh .

RUN apk update \
    && apk --no-cache --update add bash

CMD ["/bin/bash", "run-proxy.sh"]