FROM nginx:alpine
RUN rm /etc/nginx/conf.d/default.conf
COPY nginx.conf /etc/nginx/conf.d/default.conf
COPY server.crt /etc/nginx/certs/server.crt
COPY server.key /etc/nginx/certs/server.key
