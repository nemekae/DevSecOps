FROM nginx:1.27.0

RUN apt-get update
RUN apt-get -y install vim

# /user/share/nginx/html is the default location for nginx html files
COPY index.html /usr/share/nginx/html/index.html
RUN chown nginx:nginx /usr/share/nginx/html/index.html

