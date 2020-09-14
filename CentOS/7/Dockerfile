FROM panaceya/nginx-build-quic:centos-7 AS nginx-build-quic
FROM nginx:latest 
COPY --from=nginx-build-quic /usr/sbin/nginx /usr/sbin/nginx
