FROM nginx

WORKDIR /app

COPY index.html /usr/share/nginx/html
COPY nginx.conf /etc/nginx/conf.d/default.conf

EXPOSE 80/tcp

# docker run -d -p 8081:80 my-nginx