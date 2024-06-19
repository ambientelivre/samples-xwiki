ARG XWIKI_VERSION
FROM xwiki:${XWIKI_VERSION}-mysql-tomcat

ARG WEBAPPS_XWIKI=/usr/local/tomcat/webapps/ROOT

COPY extensions $WEBAPPS_XWIKI/WEB-INF/lib

