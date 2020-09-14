FROM panaceya/nginx-build-quic:ubuntu-18.04 AS nginx-build-quic
FROM nginx:latest 
COPY --from=nginx-build-quic /usr/sbin/nginx /usr/sbin/nginx
