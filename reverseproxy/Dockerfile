FROM nginx:alpine

RUN mkdir /etc/nginx/snippets
COPY snippets/proxy.conf /etc/nginx/snippets
COPY snippets/common.conf /etc/nginx/snippets

COPY nginx.conf /etc/nginx/nginx.conf
