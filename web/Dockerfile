FROM nginx
RUN rm -rf /user/share/nginx/html/index.html
COPY roboshop.conf /etc/nginx/default.d/roboshop.conf
ADD static /user/share/nginx/html/