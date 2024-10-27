FROM nginx
EXPOSE 80
RUN rm -rf /usr/share/nginx/html/*
RUN rm -rf /etc/nginx/nginx.conf
RUN rm -rf /etc/nginx/conf.d/default.conf
COPY code /usr/share/nginx/html/
COPY nginx.conf /etc/nginx/nginx.conf