# Use the httpd-parent image as base
FROM quay.io/redhattraining/httpd-parent
useradd wildfly &&
RUN chgrp -R 0 /opt/app-root && chmod -R g=u /opt/app-root
USER 1001
