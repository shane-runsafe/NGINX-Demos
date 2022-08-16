FROM runsafesecurity-docker-alkemist-repo.jfrog.io/nginx
RUN rm /etc/nginx/conf.d/*
COPY hello.conf /etc/nginx/conf.d
copy content /usr/share/nginx/html
