FROM doitandbedone/ispyagentdvr:4.2.9.0
LABEL maintainer="doitandbedone"

RUN apt update -yqq
RUN apt install rsync mc nano -yqq

EXPOSE 8090/tcp
EXPOSE 3478/udp
EXPOSE 50000-50010/udp

WORKDIR /agent
