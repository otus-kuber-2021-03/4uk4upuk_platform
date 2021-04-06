FROM nginx:latest

COPY ./app.conf /etc/nginx/conf.d/app.conf
COPY ./homework.html /app/

RUN usermod -u 1001 nginx

EXPOSE 8000