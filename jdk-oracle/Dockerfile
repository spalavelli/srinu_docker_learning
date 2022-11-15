FROM komljen/ubuntu
MAINTAINER srinivas<srinivasr6551@gmail.com>
ENV JAVA_VERSION 7
RUN\
	apt-get-update && \
	echo oracle-java${JAVA_VERSION}-installer shared/accepted-oracle-license-v1-1 select true\ | /usr/bin/bedconf-set-selection && \
	apt-get install \ oracle-java${JAVA_VERSION}-installer && \
RUN	update-alternatives --display java

