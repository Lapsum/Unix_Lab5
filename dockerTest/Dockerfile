FROM nginx:1.19.6-alpine
WORKDIR /app
COPY default.conf /etc/nginx/conf.d/default.conf
COPY index.html .
ENTRYPOINT ["nginx", "-g", "daemon off;"]