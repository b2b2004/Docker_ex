# nginx 설정 복사

FROM nginx

COPY webapp /usr/share/nginx/html
COPY conf/nginx.conf /etc/nginx/conf.d/default.conf

ENTRYPOINT ["nginx", "-g", "daemon off;"]