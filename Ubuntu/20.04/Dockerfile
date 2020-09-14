FROM nginx-build-quic:ubuntu-focal AS nginx-build-quic
FROM nginx:latest 
COPY --from=nginx-build-quic /usr/sbin/nginx /usr/sbin/nginx
