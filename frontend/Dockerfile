FROM nginx
RUN rm -rf /usr/share/nginx/html/*
COPY nginx.conf /tc/nginx/conf.d/default.conf
COPY ./template/ /usr/share/nginx/html
EXPOSE 80
CMD ["nginx", "-g", "daemon off;" ]