FROM nginx:alpine
RUN mkdir html && apk update
COPY index.html /usr/share/nginx/html
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
