FROM nginx:1.15.6

COPY nginx.conf /etc/nginx/
RUN usermod -u 1000 www-data

CMD ["nginx"]
EXPOSE 80
EXPOSE 443