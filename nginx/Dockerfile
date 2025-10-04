FROM nginx:latest
RUN mkdir -p /var/lib/nginx/proxy_cache && chown -R nginx:nginx /var/lib/nginx/proxy_cache
COPY nginx.conf /etc/nginx/nginx.conf
COPY static /etc/nginx/static