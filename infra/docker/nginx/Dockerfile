FROM nginx:1.25

WORKDIR /workspace

ENV TZ=UTC

COPY ./infra/docker/nginx/*.conf /etc/nginx/conf.d/

COPY ./src/public /workspace/public