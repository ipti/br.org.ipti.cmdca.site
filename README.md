#Docker BUILD
docker build --tag cmdca-nginx .

#Docker RUN
docker run --name cmdca-site --publish 80:80 -v D:\repositorios\ipti\br.org.ipti.cmdca.site:/usr/share/nginx/html cmdca-nginx