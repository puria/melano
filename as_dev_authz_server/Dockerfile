FROM ghcr.io/forkbombeu/didroom_microservices:stable

ENV ZENCODE_DIR=/app/authz_server
ENV PUBLIC_DIR=/app/public/authz_server
ENV BASEPATH=/authz_server
ENV MS_URL=https://dev.authz-server1.forkbomb.eu/authz_server
ENV MS_NAME=as_dev_authz_server

COPY authz_server /app/authz_server
COPY public/authz_server /app/public/authz_server

RUN make -C /app authorize
