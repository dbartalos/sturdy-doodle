FROM tutum/nginx

RUN rm /etc/nginx/sites-enabled/default || echo "There were failing tests!"
ADD sites-enabled/ /etc/nginx/sites-enabled