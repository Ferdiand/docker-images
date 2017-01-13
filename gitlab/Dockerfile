FROM gitlab/gitlab-ce
LABEL org.freenas.interactive="false"			\
      org.freenas.version="1" 			\
      org.freenas.upgradeable="true" 			\
      org.freenas.expose-ports-at-host="true" 		\
      org.freenas.autostart="true" 			\
      org.freenas.bridged="true" 			\
      org.freenas.web-ui-protocol="http" 		\
      org.freenas.web-ui-port=80 			\
      org.freenas.web-ui-path="web" 			\
      org.freenas.port-mappings="443:443/tcp,80:80/tcp,22:22/tcp" 					\
      org.freenas.volumes="[				\
          {						\
              \"name\": \"/etc/gitlab\",			\
              \"descr\": \"gitlab dir\"	\
          },						\
          {						\
              \"name\": \"/var/opt/gitlab\",			\
              \"descr\": \"opt\"		\
          }						\
          {						\
              \"name\": \"/var/log/gitlab\",			\
              \"descr\": \"log\"		\
          }						\
      ]"						\
      org.freenas.settings="[ 				\
      ]"
