FROM nginx

RUN useradd -u 1001 www-user
RUN mkdir /app && chown -R www-user:www-user /app/ /var/cache/nginx/ /var/run/

COPY ./app.conf /etc/nginx/conf.d/app.conf
COPY ./homework.html /app/

USER 1001
EXPOSE 8000