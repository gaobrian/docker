FROM ubuntu:trusty-20190515
MAINTAINER Erik Hollensbe <erik@hollensbe.org>

RUN apt-get update && apt-get install znc -y
ADD conf /.znc

CMD [ "/usr/bin/znc", "-f", "-r" ]
