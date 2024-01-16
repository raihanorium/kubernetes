FROM nginx:1.25.3-alpine
WORKDIR /usr/share/nginx/html
COPY ./build .
ENTRYPOINT ["nginx", "-g", "daemon off;"]
EXPOSE 80