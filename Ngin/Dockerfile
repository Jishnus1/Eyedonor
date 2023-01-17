FROM nginx:alpine

COPY nginx.conf /etc/nginx/nginx.conf
COPY nginx.conf /etc/nginx/conf.d/default.conf

EXPOSE 80
ENTRYPOINT [ "nginx","-g","daemon off;" ]
