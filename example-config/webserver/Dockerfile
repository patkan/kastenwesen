FROM ubuntu:14.04

RUN apt-get update
RUN apt-get install -y webfs
RUN mkdir /var/www


EXPOSE 80
CMD /usr/bin/webfsd -F -r /var/www -p 80