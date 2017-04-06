FROM vdubois/ide-template:latest

#https://download-cf.jetbrains.com/idea/ideaIU-2017.1.tar.gz
ENV INTELLIJ_VERSION 2017.1

ADD ideaIU-${INTELLIJ_VERSION}.tar.gz /opt
RUN ln -s /opt/idea* /opt/idea

CMD ["/opt/idea/bin/idea.sh"]
