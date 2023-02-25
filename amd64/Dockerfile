# syntax=docker/dockerfile:1

FROM brownant/code-server-x86
WORKDIR /
COPY ./data ./opt
RUN cd /opt && tar -zxf nodejs.tar.gzip && \
    ln -s /opt/nodejs/bin/node /usr/local/bin/ | ln -s /opt/nodejs/bin/npm /usr/local/bin/
CMD []
EXPOSE 8443